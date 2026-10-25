# Transcribe audio locally

**Task:** Produce text and subtitle files from local audio with [whisper.cpp](https://github.com/ggml-org/whisper.cpp). **Platforms:** Windows, macOS and Linux. **Preparation:** Follow the upstream quick start to obtain the program and a compatible model before disconnecting. This is a command-line workflow.

## Before disconnecting

Prepare a working `whisper-cli` binary, a downloaded model and a short audio sample. For Chinese or mixed-language speech, use a multilingual model, such as `ggml-base.bin`, rather than an English-only `.en` model. A model's speed and memory use depend on your hardware.

If the input format needs conversion, install FFmpeg in advance. The examples below assume a terminal opened in the prepared whisper.cpp directory, with `models/ggml-base.bin` available. Replace file paths with your own; keep the original recording.

## Workflow

Convert an existing recording to a 16 kHz, mono, 16-bit WAV file if needed:

```sh
ffmpeg -i input.m4a -ar 16000 -ac 1 -c:a pcm_s16le speech.wav
```

On macOS or Linux, using the usual CMake build location:

```sh
./build/bin/whisper-cli -m models/ggml-base.bin -f speech.wav -l auto -otxt -osrt -of transcript
```

On Windows PowerShell, point to the executable produced or downloaded during setup. For a CMake Release build:

```powershell
.\build\bin\Release\whisper-cli.exe -m models/ggml-base.bin -f speech.wav -l auto -otxt -osrt -of transcript
```

Binary locations differ between builds; use the location actually created by the upstream installation steps. The expected output files are `transcript.txt` and `transcript.srt`. Check the installed CLI's `--help` if your version has different options.

Run a short sample while disconnected, then play the recording against the transcript. Review names, numbers, timestamps and quiet passages. Silence and noise can produce incorrect text; the output is a draft that needs review.

## Source and verification

Based on the upstream [quick start](https://github.com/ggml-org/whisper.cpp#quick-start) and [CLI option definitions](https://github.com/ggml-org/whisper.cpp/blob/master/examples/cli/cli.cpp), reviewed on 25 October 2026. These commands were checked against documentation and source but were not executed in this session.

## 中文任务概述

先准备 whisper.cpp 程序、模型和音频转换工具。中文使用多语言模型；转换成本地 WAV 后执行转写，输出 TXT 和 SRT。命令中的程序路径取决于安装方式，需以实际文件为准。最后逐段核对录音，不能把自动转写视为已经校对的记录。
