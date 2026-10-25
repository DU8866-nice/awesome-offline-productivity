<div align="center">
  <a href="https://github.com/DU8866-nice/awesome-offline-productivity">
    <img src="media/logo.svg" width="600" height="180" alt="Awesome Offline Productivity">
  </a>
  <br>
  <br>
  <a href="https://awesome.re"><img src="https://awesome.re/badge-flat2.svg" alt="Awesome"></a>
  <br>
  <br>
  <p>Desktop tools for writing, editing and organizing local files, with offline requirements made explicit.</p>
</div>

<p align="center">
  <a href="README.zh-CN.md">简体中文</a>&nbsp;&nbsp;&nbsp;
  <a href="docs/offline-guide.md">What counts as offline?</a>&nbsp;&nbsp;&nbsp;
  <a href="contributing.md">Contribution guide</a>&nbsp;&nbsp;&nbsp;
  <a href="docs/source-review.md">Source review</a>
</p>

A practical directory of **24 applications across 8 categories**, with guides for searchable PDFs, local transcription and backups. Start with the task you need to finish, then check the platform and setup requirements for the tool you choose.

The listed tasks work without an internet connection after installation and necessary downloads. Models, OCR languages and dictionaries need preparation; LocalSend needs a local network. See [what counts as offline](docs/offline-guide.md) before choosing a tool.

## Contents

- [Start Here](#start-here)
- [Notes and Knowledge](#notes-and-knowledge)
- [Documents and PDFs](#documents-and-pdfs)
- [Images and Diagrams](#images-and-diagrams)
- [Audio and Video](#audio-and-video)
- [Local AI and Transcription](#local-ai-and-transcription)
- [Search and Automation](#search-and-automation)
- [Files and Backups](#files-and-backups)
- [Reading and References](#reading-and-references)
- [Selection and Review](#selection-and-review)
- [Related](#related)

## Start Here

These walkthroughs explain what to prepare and how to check the result. For individual applications, browse the categories below.

| I want to | Start with | Check the result |
| --- | --- | --- |
| Search text inside a scanned document. | [Make Scanned PDFs Searchable](guides/searchable-pdfs.md). | Search for known words and compare copied text with the scan. |
| Turn a recording into text without a cloud API. | [Transcribe Audio Locally](guides/local-transcription.md). | Compare the TXT and SRT output with the recording. |
| Keep an encrypted backup on an external drive. | [Back Up to an External Drive](guides/local-backup.md). | Restore to a separate folder and open the restored files. |

## Notes and Knowledge

- [Joplin](https://joplinapp.org/) - Local notebooks and to-do lists with offline search and optional synchronization. `Windows, macOS, Linux`.
- [Obsidian](https://obsidian.md/) - Markdown notes stored in local folders, with backlinks and optional sync; proprietary software. `Windows, macOS, Linux`.
- [Zettlr](https://www.zettlr.com/) - Markdown writing and research notes stored on your computer, with citation integration. `Windows, macOS, Linux`.

## Documents and PDFs

- [LibreOffice](https://www.libreoffice.org/) - Desktop word processing, spreadsheets and presentations that open and save local documents. `Windows, macOS, Linux`.
- [NAPS2](https://www.naps2.com/) - Scan or import pages and create searchable PDFs; download OCR language packs before disconnecting. `Windows, macOS, Linux`.
- [PDFsam Basic](https://pdfsam.org/pdfsam-basic/) - Split, merge, rotate and extract PDF pages locally using the Basic desktop edition. `Windows, macOS, Linux`.

## Images and Diagrams

- [draw.io Desktop](https://github.com/jgraph/drawio-desktop) - Flowcharts and diagrams saved as local files in the standalone desktop application. `Windows, macOS, Linux`.
- [GIMP](https://www.gimp.org/) - Edit and retouch local images with layers, selections and reusable editing tools. `Windows, macOS, Linux`.
- [Krita](https://krita.org/) - Digital painting and illustration with local project files and configurable brushes. `Windows, macOS, Linux`.

## Audio and Video

- [Audacity](https://www.audacityteam.org/) - Record, trim and mix audio locally; cloud sharing is outside this list's scope. `Windows, macOS, Linux`.
- [HandBrake](https://handbrake.fr/) - Convert local video files into supported output formats with desktop presets. `Windows, macOS, Linux`.
- [Shotcut](https://shotcut.org/) - Edit local video on a timeline with filters, transitions and export controls. `Windows, macOS, Linux`.

## Local AI and Transcription

- [Jan](https://jan.ai/) - Desktop chat with downloaded language models; select a local model instead of a cloud provider. `Windows, macOS, Linux`.
- [Ollama](https://ollama.com/) - Run downloaded language models on your machine; cloud models and web search require internet access. `Windows, macOS, Linux`.
- [whisper.cpp](https://github.com/ggml-org/whisper.cpp) - Transcribe local audio with on-device speech recognition after downloading model weights. `Windows, macOS, Linux`.

## Search and Automation

- [Espanso](https://espanso.org/) - Expand typed shortcuts into reusable text snippets using local configuration files. `Windows, macOS, Linux`.
- [Flow Launcher](https://www.flowlauncher.com/) - Search Windows applications and local files from a keyboard launcher; web plugins need internet. `Windows`.
- [PowerToys](https://github.com/microsoft/PowerToys) - Windows utilities for window layouts, bulk file renaming and other local desktop tasks. `Windows`.

## Files and Backups

- [7-Zip](https://www.7-zip.org/) - Create and extract local archives with the Windows desktop application. `Windows`.
- [LocalSend](https://localsend.org/) - Transfer files between nearby devices without internet; a reachable local network is required. `Windows, macOS, Linux; mobile companions`.
- [restic](https://restic.net/) - Create encrypted, versioned backups in a local directory or attached drive using the command line. `Windows, macOS, Linux`.

## Reading and References

- [calibre](https://calibre-ebook.com/) - Organize, read and convert locally stored e-books; downloading books or metadata needs internet. `Windows, macOS, Linux`.
- [GoldenDict-ng](https://xiaoyifang.github.io/goldendict-ng/) - Look up words in local dictionaries; obtain compatible dictionary files before going offline. `Windows, macOS, Linux`.
- [Zotero](https://www.zotero.org/) - Organize references and annotate locally saved PDFs; online capture and synchronization need internet. `Windows, macOS, Linux`.

## Selection and Review

Entries are selected for a specific task that can be completed locally after setup. Each entry links to an official website or canonical repository, states its desktop platforms and identifies relevant offline conditions.

The [source review](docs/source-review.md) records the documentation used for each tool. Check the official download page for supported OS versions and hardware. Optional cloud services and online plugins have separate requirements; a desktop application does not make every feature offline.

Suggestions should add a useful option within the categories above and include evidence for the offline task. Use the [contribution guide](contributing.md) to propose an addition or correct an entry.

## Related

- [Awesome](https://github.com/sindresorhus/awesome#readme) - Curated lists about many different topics.
- [Awesome Productivity](https://github.com/jyguyomarch/awesome-productivity#readme) - General productivity methods, applications and reading.
- [Awesome Local-First](https://github.com/schickling/awesome-local-first#readme) - Local-first applications and development concepts.
- [Awesome Selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted#readme) - Software that can be hosted on your own servers.

## Contributing

Suggestions and corrections are welcome. Read the [contribution guide](contributing.md) and provide a primary source for the specific offline task.

## Footnotes

Offline means the listed task can run after installation and required downloads; it does not promise zero network requests. Some tools have optional cloud features, and LocalSend needs a local network. See the [offline guide](docs/offline-guide.md).

This first edition is AI-assisted and documentation-reviewed as of 25 October 2026. The applications and workflows were not runtime-tested in this session. Evidence and review limits are recorded in the [source review](docs/source-review.md).
