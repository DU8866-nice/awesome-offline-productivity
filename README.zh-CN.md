<div align="center">
  <a href="https://github.com/DU8866-nice/awesome-offline-productivity">
    <img src="media/logo.svg" width="600" height="180" alt="Awesome Offline Productivity">
  </a>
  <br>
  <br>
  <a href="https://awesome.re"><img src="https://awesome.re/badge-flat2.svg" alt="Awesome"></a>
  <br>
  <br>
  <p>按任务查找可离线使用的桌面工具，先看用途，再看系统与准备条件。</p>
</div>

<p align="center">
  <a href="README.md">English</a>&nbsp;&nbsp;&nbsp;
  <a href="docs/offline-guide.md">离线条件说明</a>&nbsp;&nbsp;&nbsp;
  <a href="contributing.md">贡献指南</a>&nbsp;&nbsp;&nbsp;
  <a href="docs/source-review.md">资料核查记录</a>
</p>

这里整理了 **8 个分类、24 个应用**，以及扫描件转可搜索 PDF、本地音频转写和外接硬盘备份的使用流程。先找到要完成的任务，再查看工具支持的系统和使用前需要准备的内容。

本清单所说的“离线”，是指安装并完成必要下载后，条目描述的任务可不依赖互联网进行。模型、OCR 语言包和词典需要提前准备；LocalSend 仍需要本地网络。选择工具前可先阅读[离线条件说明](docs/offline-guide.md)。

## 目录

- [从这里开始](#start-here)
- [笔记与知识管理](#notes-and-knowledge)
- [文档与 PDF](#documents-and-pdfs)
- [图像与图示](#images-and-diagrams)
- [音频与视频](#audio-and-video)
- [本地 AI 与语音转写](#local-ai-and-transcription)
- [搜索与自动化](#search-and-automation)
- [文件与备份](#files-and-backups)
- [阅读与文献](#reading-and-references)
- [收录与核查标准](#selection-and-review)
- [相关清单](#related)

<a id="start-here"></a>

## 从这里开始

以下流程说明了准备步骤和结果检查方法。只想找某一类应用，可以继续浏览下方分类。

| 我想完成的任务 | 对应流程 | 怎样检查结果 |
| --- | --- | --- |
| 在扫描件中搜索文字。 | [把扫描件变成可搜索 PDF](guides/searchable-pdfs.md)。 | 搜索已知词语，并把复制出的文字与扫描件核对。 |
| 不用云端 API，把录音转成文字。 | [在本地转写音频](guides/local-transcription.md)。 | 对照录音检查 TXT 文字和 SRT 字幕。 |
| 在外接硬盘上保留加密备份。 | [备份到外接硬盘](guides/local-backup.md)。 | 恢复到另一个目录，实际打开恢复后的文件。 |

<a id="notes-and-knowledge"></a>

## 笔记与知识管理

- [Joplin](https://joplinapp.org/) - 本地笔记本和待办清单，支持离线搜索，同步功能可选。 `Windows, macOS, Linux`。
- [Obsidian](https://obsidian.md/) - 以本地 Markdown 文件保存笔记，支持双向链接；同步可选，软件为闭源。 `Windows, macOS, Linux`。
- [Zettlr](https://www.zettlr.com/) - 将写作和研究笔记保存在本机的 Markdown 编辑器，支持引文集成。 `Windows, macOS, Linux`。

<a id="documents-and-pdfs"></a>

## 文档与 PDF

- [LibreOffice](https://www.libreoffice.org/) - 可在本机打开、编辑和保存文档、表格及演示文稿的桌面办公套件。 `Windows, macOS, Linux`。
- [NAPS2](https://www.naps2.com/) - 扫描或导入页面并制作可搜索 PDF；OCR 语言包需提前下载。 `Windows, macOS, Linux`。
- [PDFsam Basic](https://pdfsam.org/pdfsam-basic/) - 使用 Basic 桌面版在本机拆分、合并、旋转和提取 PDF 页面。 `Windows, macOS, Linux`。

<a id="images-and-diagrams"></a>

## 图像与图示

- [draw.io Desktop](https://github.com/jgraph/drawio-desktop) - 使用独立桌面版绘制流程图和示意图，并保存为本地文件。 `Windows, macOS, Linux`。
- [GIMP](https://www.gimp.org/) - 使用图层、选区等工具在本地编辑与修饰图片。 `Windows, macOS, Linux`。
- [Krita](https://krita.org/) - 使用本地工程文件和可配置画笔进行数字绘画与插画创作。 `Windows, macOS, Linux`。

<a id="audio-and-video"></a>

## 音频与视频

- [Audacity](https://www.audacityteam.org/) - 在本机录制、剪切和混合音频；本清单不涉及云端分享功能。 `Windows, macOS, Linux`。
- [HandBrake](https://handbrake.fr/) - 通过桌面预设将本地视频转换成支持的输出格式。 `Windows, macOS, Linux`。
- [Shotcut](https://shotcut.org/) - 通过时间线、滤镜、转场和导出设置编辑本地视频。 `Windows, macOS, Linux`。

<a id="local-ai-and-transcription"></a>

## 本地 AI 与语音转写

- [Jan](https://jan.ai/) - 使用已下载的语言模型进行桌面对话；需选择本地模型而非云端服务。 `Windows, macOS, Linux`。
- [Ollama](https://ollama.com/) - 在本机运行已下载的语言模型；云端模型和网页搜索需要联网。 `Windows, macOS, Linux`。
- [whisper.cpp](https://github.com/ggml-org/whisper.cpp) - 下载模型权重后，使用设备端语音识别转写本地音频。 `Windows, macOS, Linux`。

<a id="search-and-automation"></a>

## 搜索与自动化

- [Espanso](https://espanso.org/) - 用本地配置把输入的快捷缩写展开为可复用文字片段。 `Windows, macOS, Linux`。
- [Flow Launcher](https://www.flowlauncher.com/) - 通过键盘启动器搜索 Windows 应用和本地文件；网络插件需要联网。 `Windows`。
- [PowerToys](https://github.com/microsoft/PowerToys) - 提供窗口布局、批量文件重命名等本地桌面功能的 Windows 工具集。 `Windows`。

<a id="files-and-backups"></a>

## 文件与备份

- [7-Zip](https://www.7-zip.org/) - 使用 Windows 桌面版创建和解压本地压缩文件。 `Windows`。
- [LocalSend](https://localsend.org/) - 无需互联网即可向附近设备传输文件，但需要可互通的本地网络。 `Windows, macOS, Linux; mobile companions`。
- [restic](https://restic.net/) - 通过命令行，在本地目录或外接硬盘上创建加密且带版本的备份。 `Windows, macOS, Linux`。

<a id="reading-and-references"></a>

## 阅读与文献

- [calibre](https://calibre-ebook.com/) - 整理、阅读和转换已保存在本地的电子书；下载书籍或元数据需要联网。 `Windows, macOS, Linux`。
- [GoldenDict-ng](https://xiaoyifang.github.io/goldendict-ng/) - 使用本地词典文件查词；离线前需准备兼容且有权使用的词典数据。 `Windows, macOS, Linux`。
- [Zotero](https://www.zotero.org/) - 管理文献并批注本地 PDF；在线抓取和同步功能需要联网。 `Windows, macOS, Linux`。

<a id="selection-and-review"></a>

## 收录与核查标准

收录以具体的本地任务为依据：安装和准备完成后，用户应能在不依赖互联网的情况下完成条目描述的操作。每项都提供官方站点或规范仓库链接，标明桌面系统，并说明影响离线使用的条件。

[资料核查记录](docs/source-review.md)列出了各工具的依据。操作系统版本和硬件要求以官方下载页为准；可选云服务和网络插件需要单独检查，桌面应用中的所有功能不一定都能离线使用。

欢迎补充现有分类中有用的选择，或纠正过时条目。请按[贡献指南](contributing.md)提供具体用途和官方依据。首版工作流以英文为主，并附中文任务概述。

<a id="related"></a>

## 相关清单

- [Awesome](https://github.com/sindresorhus/awesome#readme) - 多个主题的精选清单总目录。
- [Awesome Productivity](https://github.com/jyguyomarch/awesome-productivity#readme) - 通用效率方法、应用和阅读资料。
- [Awesome Local-First](https://github.com/schickling/awesome-local-first#readme) - 本地优先应用与开发概念。
- [Awesome Selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted#readme) - 可在自有服务器部署的软件。

## 参与贡献

欢迎补充和纠错。请先阅读[贡献指南](contributing.md)，并为具体离线任务提供官方来源。

## 说明

这里的“离线”指安装和必要下载完成后，所列核心任务可以不依赖互联网完成，不代表软件绝不发起网络请求。部分工具有可选云功能；LocalSend 仍需要本地网络。详情见[离线条件说明](docs/offline-guide.md)。

首版由 AI 辅助整理，资料核查日期为 2026 年 10 月 25 日。本次未逐一安装测试所列应用或执行工作流；[核查记录](docs/source-review.md)注明了依据和限制。工作流说明以英文为主，并附中文任务概述。
