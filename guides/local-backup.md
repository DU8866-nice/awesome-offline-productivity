# Back up to an external drive

**Task:** Keep encrypted, versioned copies of a working folder on an attached drive using [restic](https://restic.net/). **Platforms:** Windows, macOS and Linux. This walkthrough uses Windows PowerShell paths; adapt paths for your system.

## Before disconnecting

Install restic, prepare an external drive with enough space, and decide where to keep its repository password. The backup requires that password to restore. Use a separate destination outside the source folder; an independent drive protects against more failures than a second folder on the same drive.

In these examples, `C:\Work` is the existing source folder and `E:\OfflineBackup` is a new backup location on the attached drive. Replace both with the real paths for your machine. The commands create a backup; they do not remove the originals.

## Workflow

Initialize the backup repository once:

```powershell
restic -r E:\OfflineBackup init
```

Create a snapshot of the working folder and list the saved snapshots:

```powershell
restic -r E:\OfflineBackup backup C:\Work
restic -r E:\OfflineBackup snapshots
```

Check the repository's structure and verify that a restore can be opened in a separate location:

```powershell
restic -r E:\OfflineBackup check
restic -r E:\OfflineBackup restore latest --target C:\RestoreCheck
```

Choose a new restore destination and inspect the restored folder tree. Open several restored files and compare them with the originals. The normal `check` command validates repository structure; reading all stored data requires additional options described in the official documentation. Do not call a backup verified solely because a snapshot appears in the list.

## Source and verification

See the official [local repository preparation](https://restic.readthedocs.io/en/stable/030_preparing_a_new_repo.html#local), [backup guide](https://restic.readthedocs.io/en/stable/040_backup.html), [restore guide](https://restic.readthedocs.io/en/stable/050_restore.html) and [repository checks](https://restic.readthedocs.io/en/stable/045_working_with_repos.html). Reviewed on 25 October 2026; the commands were not executed in this session.

## 中文任务概述

提前安装 restic，准备独立外接硬盘和仓库密码。初始化本地备份仓库、创建快照，再恢复到另一个目录并打开文件核对。示例盘符和目录需要替换为实际路径。仅看到快照或普通检查通过，并不等于已完整验证所有备份数据。
