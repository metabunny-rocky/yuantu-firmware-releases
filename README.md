# yuantu firmware releases

Auto-generated binaries for [yuqiulin2021/yuantu](https://github.com/yuqiulin2021/yuantu).

**Do not edit manually.** This repo is a public distribution endpoint for
compiled ESP32-S3 firmware. Every push to the source repo triggers CI which
publishes a per-branch Release here containing:

| file | flash offset |
|---|---|
| `merged.bin` | `0x0` (single-shot) |
| `bootloader.bin` | `0x0` |
| `partition-table.bin` | `0x8000` |
| `waveshare_openclaw.bin` | `0x10000` |

Flash via the web tool at
https://github.com/yuqiulin2021/yuantu/blob/main/flasher/index.html
(clone + open in Chrome with Web Serial support).
