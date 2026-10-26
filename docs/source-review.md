# Source review

Review date: **25 October 2026**. All entries were checked against official repositories or product documentation. Repository availability and archived status were checked through GitHub. This is a documentation review, not an installation test, security audit or confirmation that every feature works offline.

The application source repositories listed below were not archived at review time. Mirrors and release-only repositories are not treated as complete product specifications; relevant official product pages are included where needed.

| Resource | Offline condition | Primary evidence |
| --- | --- | --- |
| Joplin | Optional sync: 普通本地笔记不需要云同步。 | [Source 1](https://github.com/laurent22/joplin/blob/dev/README.md) |
| Koru | Optional sync: 笔记保存在本机数据库中，读写可离线；设备间点对点同步、可选的 Koru Cloud 登录和更新需要联网。Linux 版本为 nightly 预览版。 | [Source 1](https://github.com/koruworks/mono/blob/main/README.md) |
| Obsidian | Optional sync: 本地笔记可离线；同步、发布及部分插件需要联网。 | [Source 1](https://github.com/obsidianmd/obsidian-releases/blob/master/README.md) · [Source 2](https://obsidian.md/) |
| Zettlr | Local files: 使用本地文件；部分导出格式可能需要预装 Pandoc 或 LaTeX。 | [Source 1](https://github.com/Zettlr/Zettlr/blob/develop/README.md) · [Source 2](https://www.zettlr.com/) |
| LibreOffice | Local files: 本地办公和导出可离线；联机协作不在收录范围内。 | [Source 1](https://github.com/LibreOffice/core/blob/master/README.md) |
| NAPS2 | Prepare assets: 先下载 OCR 语言包；设备驱动也需事先准备。 | [Source 1](https://github.com/cyanfish/naps2/blob/master/README.md) · [Source 2](https://www.naps2.com/doc/ocr) |
| PDFsam Basic | Local files: 本条仅指 Basic 桌面版的本地 PDF 操作。 | [Source 1](https://github.com/torakiki/pdfsam/blob/master/README.md) · [Source 2](https://pdfsam.org/pdfsam-basic/) |
| draw.io Desktop | Local files: 使用桌面版和本地文件；更新检查可能联网。 | [Source 1](https://github.com/jgraph/drawio-desktop/blob/dev/README.md) |
| GIMP | Local files: 核心图像编辑基于本地文件；第三方插件另行评估。 | [Source 1](https://github.com/GNOME/gimp/blob/master/README) · [Source 2](https://www.gimp.org/) |
| Krita | Local files: 画笔和素材若未内置，需要提前准备。 | [Source 1](https://github.com/KDE/krita/blob/master/README.md) |
| Audacity | Local files: 本条指本地录制和编辑，不包括云服务。 | [Source 1](https://github.com/audacity/audacity/blob/master/README.md) |
| HandBrake | Local files: 处理已存储在本机的视频；不是在线视频下载工具。 | [Source 1](https://github.com/HandBrake/HandBrake/blob/master/README.markdown) |
| Shotcut | Local files: 媒体和所用素材需已保存在本地。 | [Source 1](https://github.com/mltframework/shotcut/blob/master/README.md) |
| Jan | Prepare assets: 提前下载适合硬件的模型，离线时不使用云端 API。 | [Source 1](https://github.com/janhq/jan/blob/main/README.md) |
| Ollama | Prepare assets: 先下载本地模型；官方 FAQ 提供关闭云功能的方法。 | [Source 1](https://github.com/ollama/ollama/blob/main/README.md) · [Source 2](https://docs.ollama.com/faq) |
| whisper.cpp | Prepare assets: 需先准备模型、程序和音频格式转换工具。 | [Source 1](https://github.com/ggml-org/whisper.cpp/blob/master/README.md) |
| Espanso | Local files: 本地文本展开可离线；外部脚本或扩展包可能需要联网。 | [Source 1](https://github.com/espanso/espanso/blob/dev/README.md) |
| Flow Launcher | Local files: 离线范围仅包括本地应用、文件和系统功能。 | [Source 1](https://github.com/Flow-Launcher/Flow.Launcher/blob/dev/README.md) |
| PowerToys | Local files: 仅收录本地工具功能；联网和 AI 扩展需单独检查。 | [Source 1](https://github.com/microsoft/PowerToys/blob/main/README.md) |
| 7-Zip | Local files: 此处平台指桌面图形界面，不泛指所有命令行移植版。 | [Source 1](https://github.com/ip7z/7zip/blob/main/README.md) · [Source 2](https://www.7-zip.org/) |
| LocalSend | LAN required: 两台设备需要本地网络连接；不是无任何网络也能传输。 | [Source 1](https://github.com/localsend/localsend/blob/main/README.md) |
| restic | Local storage: 离线方案使用本地或外接盘仓库；远程存储需要网络。 | [Source 1](https://github.com/restic/restic/blob/master/README.md) |
| calibre | Local files: 离线使用本地书库；联网抓取元数据不属于离线功能。 | [Source 1](https://github.com/kovidgoyal/calibre/blob/master/README.md) |
| GoldenDict-ng | Prepare assets: 需要自行提供兼容词典；在线词典功能不属于离线范围。 | [Source 1](https://github.com/xiaoyifang/goldendict-ng/blob/staged/README.md) · [Source 2](https://xiaoyifang.github.io/goldendict-ng/) |
| Zotero | Optional sync: 阅读、整理已保存的资料可离线；自动抓取元数据需要联网。 | [Source 1](https://github.com/zotero/zotero/blob/main/README.md) · [Source 2](https://www.zotero.org/support/quick_start_guide) |

## Review limits
- Platform names describe supported desktop families, not every OS version or CPU architecture. Check the official download page for your machine.
- Offline scope is restricted to the task described in the readme. Downloads, updates, optional cloud integrations and remote resources may require internet.
- No blanket claim is made about telemetry, security, price or open-source status. Obsidian is proprietary.
- LocalSend is internet-independent but requires a reachable local network. restic is offline only when a local destination is selected.
- Language models, OCR packs, media and dictionaries must be obtained before disconnecting.
- The three workflow guides are source-based walkthroughs, not reported test results.
## Maintaining this record
For each contribution, check the official source again and record the date, operating system, exact local task, required assets and optional online features. If someone performs a runtime test, add a dated test record including the application version and evidence rather than silently upgrading this documentation review to a test claim.
