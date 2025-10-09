# flipper-clean-n-go

Cleaned-up, organized, and Flipper-ready version of the [UberGuidoZ/Flipper](https://github.com/UberGuidoZ/Flipper) repo.

This project filters out everything unnecessary and keeps **only files that actually work on your Flipper Zero**, properly sorted into the correct folder structure — so you can just **copy and go**.

## What it does

- Cleans the original [UberGuidoZ/Flipper](https://github.com/UberGuidoZ/Flipper) content
- Keeps only files usable on the Flipper Zero
- Automatically sorts everything into the correct folder structure
- Ready to copy directly to your device — no extra steps

## Folder structure

```text
├─ badusb/
│  └─ external/
├─ infrared/
│  └─ external/
├─ nfc/
│  └─ external/
└─ subghz/
   ├─ external/
   ├─ playlist/
   │  └─ external/
   └─ remote/
      └─ external/
```

## Usage

1. Download the latest release or clone the repo:

   ```bash
   git clone https://github.com/navysuntum/flipper-clean-n-go.git
   ```

2. Copy the repo contents to your Flipper Zero SD card.
3. Flip away ⚡

## Why

The [UberGuidoZ/Flipper](https://github.com/UberGuidoZ/Flipper) repository is an amazing playground full of experiments, tools, and community creations — but it’s also huge and full of content that doesn’t always belong directly on the device.  
**flipper-clean-n-go** exists to make it _simple and lightweight_ — only the files you need, ready to use.

## Credits

- Original content: [UberGuidoZ/Flipper](https://github.com/UberGuidoZ/Flipper)
- Cleanup & structure: [navysuntum](https://github.com/navysuntum)
