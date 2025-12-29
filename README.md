# WeChat OCR Plugin for Bob

A [Bob](https://bobtranslate.com/) plugin that utilizes WeChat's OCR engine for high-accuracy text recognition.

## Install Bob

[![Download on the Mac App Store](https://cdn.ripperhe.com/oss/master/2022/0626/Download_on_the_Mac_App_Store_Badge_US-UK_RGB_blk_092917.svg)](https://apps.apple.com/cn/app/id1630034110#?platform=mac)

## Installation

1. Download the latest release `.bobplugin` file from [Releases](https://github.com/missuo/bob-plugin-wechat-ocr/releases).
2. Double-click the downloaded file to install it into Bob.

## Configuration

This plugin works out of the box with the default API server.

- **WeChat API Base URL**: You can configure a custom API endpoint if needed.
  - Default: `https://ocr-api.missuo.me`

## Self-hosting API

You can deploy the OCR API server using [wxocr](https://github.com/missuo/wxocr) or simply run:

```bash
git clone https://github.com/missuo/wxocr.git
cd wxocr
docker compose up -d --build
```

## Development

1. Clone this repository.
2. Modify `src/main.js` or `src/info.json`.
3. Zip the contents of `src` into a `.bobplugin` file to test.

## Credits

- [missuo](https://github.com/missuo)
