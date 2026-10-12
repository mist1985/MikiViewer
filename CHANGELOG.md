# Changelog

## 1.6.0

- Protect Privacy finds much more: names and usernames, dates (such as birth and visit dates), SSN, passport, driver's licence and tax ID numbers, card expiry dates and CVV codes, bank, routing, SWIFT and loan numbers, medical record and patient, member and policy numbers, IP and MAC addresses, web links and file paths, and passwords, PINs, API keys, tokens and private keys. A value after a label ("Passport No: X1234567") is hidden while the label stays readable.
- Protect Privacy finds every face in group photos and collages; small faces in a large image used to be missed.
- Card numbers are found when their groups are printed far apart, as on a real card.

## 1.5.1

- Hide anything by hand: select an area, or some recognized text, then right-click and choose Blur, Pixelate or Black Out. The options are at the top of the menu.
- Tools ▸ Redact Selection is now called Hide Selection and also works on selected text.
- Show hidden areas again one at a time: right-click a blurred face or blacked-out text and choose Show Again, or Show All. Works for Protect Privacy and for areas you hid by hand. The original pixels are kept only in memory while you edit and are never written to the saved file.

## 1.5.0

- **Protect Privacy** (toolbar ✋ or Tools ▸ Protect Privacy…): finds faces, email addresses, phone numbers, payment card numbers, IBANs, Macedonian ЕМБГ numbers and street addresses in the image, outlines them, and hides the ones you keep ticked: faces blurred, pixelated or blacked out; text blacked out by default. Card, IBAN and ЕМБГ numbers are checked with their checksums, so random digits aren't flagged. Undo brings everything back.
- **Remove location and camera details** (GPS, camera model, date taken, author) from the saved file.
- **Redact Selection** (Tools menu or right-click a selection): black out, pixelate or blur anything else, such as a licence plate or a signature. Oval and lasso selections keep their shape.

## 1.4.0

- **Crop** button in the toolbar. Click it (or press ⌘K) and a crop frame appears straight away: drag its handles or move it, pick a shape (Free, Original, Square, 4:3, 3:2, 16:9), then press Return or click Crop. Escape cancels. If you've already selected an area, Crop uses it immediately.
- **Right-click on text in an image**: Look Up, Translate (Google Translate), Search With Google, Copy Text and Share Text. Right-clicking a word selects it.
- **Copy Subject / Share Subject**: lifts the main person, animal or object out of the photo onto a transparent background.
- **Share Image** from the right-click menu.

## 1.3.3

- New app icon: the MikiViewer budgie.

## 1.3.2

- **Delete** now asks for confirmation before moving the image to the Trash. Cancel is the default, so pressing Return never deletes by accident.

## 1.3.1

- **Delete** button in the toolbar moves the current image to the Trash (also ⌘⌫).
- The background removal tool is now called **Remove Background**.
- MikiViewer is now proprietary software: license terms and third-party notices are included (Help ▸ MikiViewer License, Help ▸ Third-Party Notices).
- The source code is now private; [mist1985/MikiViewer](https://github.com/mist1985/MikiViewer) hosts the downloads and release notes.

## 1.3.0

- **Select text right on the image**: text is recognized in the background as soon as an image opens. Drag over it to select from any point to any other (across lines), double-click for a word, triple-click for a line, then ⌘C or right-click ▸ Copy Text.
- Dragging outside text still makes a normal rectangular selection.
- New installer (`MikiViewer.pkg`) that removes the previous version before installing.

## 1.2

- **Recognize Again** in the Extracted Text panel now reads the current selection instead of the first one.
- Double-click a line of text to copy it (superseded by text selection in 1.3.0).

## 1.1

- **Text recognition (OCR)** in English and Macedonian: Tools ▸ Extract Text (⇧⌘T) or the toolbar button. Works on the whole image or on a selection.
- **OCR Languages** window to download about 120 more languages (Tesseract models).
- Macedonian letters that the standard models miss (Ѓ, Ќ, Љ, Ѕ) are handled, as are lines that mix English and Macedonian.

## 1.0

- Image viewer and editor: thumbnails, zoom, slideshow, markup (shapes, text, sketch, signatures), crop, rotate, color adjustments, background removal, export.
- New name and icon: MikiViewer.
