# What counts as offline

This list evaluates a **specific everyday task**, rather than every feature of an application. Install the application, required codecs, language packs, models, dictionaries and other assets before disconnecting.

## Conditions

| Condition | Meaning | Examples |
| --- | --- | --- |
| Local files | The listed task uses files on your device after setup. | PDFsam Basic, GIMP, Shotcut. |
| Prepare assets | Extra data must already be downloaded. | NAPS2 OCR languages, local AI models, dictionary files. |
| Optional sync | Local work is possible without the optional synchronization service. | Joplin, Obsidian, Zotero. |
| LAN required | Internet access is unnecessary, but devices must communicate over a local network. | LocalSend. |
| Local storage | Choose a local or attached backup destination; remote destinations have different requirements. | restic. |

Offline-capable does not mean that the application never checks for updates, that every plugin runs locally, or that the software is open source. Use a local model rather than a cloud provider in Jan or Ollama. Read [Ollama's FAQ](https://docs.ollama.com/faq) for its local-only configuration.

## How to check a tool yourself

1. Record its exact version, operating system and the task you want to complete.
2. Download the assets and prepare a small local input file while connected.
3. Disconnect from the internet and restart the application. For LocalSend, preserve the local network while removing its internet connection.
4. Complete the task, save the result and reopen it. Check that the result is useful, not just that the application starts.
5. Record the input, steps and result, including limitations. This verifies the task under those conditions; a separate network audit is needed to assess all background traffic.

## 中文说明

本清单中的“离线可用”针对条目描述的具体任务。软件、语言包、模型和素材需提前准备；云同步、网页搜索和云端模型不属于离线承诺。LocalSend 无需互联网，但两台设备仍需要本地网络。首版依据官方文档整理，没有把“查到官方说明”写成“已经逐一实测”。
