<p align="center"><img src="icon.png" width="128" alt="MikiViewer icon"></p>

<h1 align="center">MikiViewer</h1>

<p align="center">A fast image viewer and editor for macOS that can also read the text in your images, in English, Macedonian and about 120 other languages.</p>

<p align="center"><a href="https://mist1985.github.io/MikiViewer/"><b>Download the latest version</b></a></p>

This repository hosts MikiViewer's download page and releases. MikiViewer is proprietary software; its source code is not public.

## Features

- **View**: open images or whole folders, browse with thumbnails, zoom, full screen and slideshow.
- **Mark up**: shapes, arrows, text, sketching, signatures and a loupe, all editable until you save.
- **Edit**: crop, rotate, flip, resize, color adjustments, auto levels, and one-click background removal.
- **Select text on the image**: text is recognized as soon as an image opens. Drag across it to select exactly what you want, double-click for a word, triple-click for a line, then press ⌘C.
- **Extract Text** (⇧⌘T): recognizes the whole image, or just the area you selected, into an editable panel you can copy or save.
- **OCR languages**: English and Macedonian are built in, including Ѓ, Ќ, Љ and Ѕ. Download others from Tools ▸ OCR Languages….
- **Protect Privacy**: one click finds faces, emails, phone numbers, card numbers, IBANs and Macedonian ЕМБГ numbers, and hides them. It can also strip location and camera details from the file.
- **Hide anything by hand, show it again**: select an area or some text, right-click and choose Blur, Pixelate or Black Out. Right-click a hidden area and choose Show Again to bring back just that one.
- **Crop in one click**: a crop frame appears straight away; drag it, pick a shape (Square, 4:3, 16:9…), press Return.
- **Right-click on text**: Look Up, Translate, Search With Google, Copy or Share; **Copy Subject** lifts the main object out of a photo.

## Install

1. Download **MikiViewer.pkg** from the [download page](https://mist1985.github.io/MikiViewer/) or the [latest release](https://github.com/mist1985/MikiViewer/releases/latest).
2. Open it and follow the installer. Any previous version is removed first; your downloaded OCR languages and settings are kept.

Prefer drag-and-drop? Download **MikiViewer.dmg** and drag MikiViewer onto Applications (choose *Replace* when asked).

**First launch:** MikiViewer isn't notarized by Apple, so macOS blocks the first launch. Right-click the installer (or the app) and choose **Open**, or allow it under System Settings ▸ Privacy & Security.

**Requires** macOS 26 or later on an Apple silicon Mac.

### Uninstall

Drag `/Applications/MikiViewer.app` to the Trash. To also remove downloaded OCR languages and settings:

```sh
rm -rf ~/Library/Application\ Support/MikiViewer
defaults delete com.mihajlo.imageviewer
```

## License

Copyright © 2026 Mihajlo Stojanovski. All rights reserved.

MikiViewer is free to download and use, but it is not open source: it may not be redistributed, resold, modified or reverse engineered. See [LICENSE](LICENSE) for the full terms.

MikiViewer includes open-source components (such as [Tesseract](https://github.com/tesseract-ocr/tesseract)) used under their own licenses; see [ThirdPartyNotices.txt](ThirdPartyNotices.txt).
