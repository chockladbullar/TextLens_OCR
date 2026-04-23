# TextLens OCR

**Read text from Azerbaijani images and PDFs on your Mac.**

TextLens OCR is a free, local app that extracts text from images and PDF files using Tesseract. It runs entirely on your Mac — no internet connection needed after setup, and your files never leave your computer.

---

## Download

1. Click the green **Code** button at the top of this page
2. Choose **Download ZIP**
3. Unzip the downloaded file — you will get a folder called `textlens-ocr-main`

---

## Requirements

- Mac with Apple Silicon (M1, M2, M3) or Intel
- macOS 12 or later
- Internet connection during setup (not needed afterwards)
- About 1 GB of free storage

---

## Setup (One Time Only)

1. Open the `textlens-ocr-main` folder
2. Double-click **TextLens OCR.app**
3. If a security dialog appears, right-click **TextLens OCR.app** and choose **Open**, then click **Open** in the dialog

   ![Mac security dialog](screenshots/security-dialog.png)

4. A welcome message will appear — click **OK** to start the installation
5. A Terminal window will open showing installation progress — **leave it open**

   ![Installer running](screenshots/installer-running.png)

6. If a dialog appears asking to install developer tools, click **Install**, wait for it to finish, then press **Enter** in the Terminal window
7. When you see **Installation Complete**, press Enter to close the window

> The installation takes about 10–15 minutes. You can leave it running in the background.

---

## Using the App

After setup, double-click **TextLens OCR.app** any time you want to use it.

1. Select a language from the dropdown (Azerbaijani is default)
2. Drag and drop an image or PDF, or click to browse

   ![TextLens app in browser](screenshots/app-browser.png)

3. Click **Extract Text**
4. For PDFs, a progress bar shows which page is being processed

   ![PDF processing progress](screenshots/pdf-progress.png)

5. When done, save the result as **TXT**, **Word**, **PDF**, or **EPUB**

   ![Export options](screenshots/export-options.png)

> To stop the app, close the Terminal window that opens. The browser tab can be closed any time.

---

## Supported Languages

| Option | Use for |
|--------|---------|
| Azerbaijani | Azerbaijani text (Latin script) |
| Azerbaijani + English | Documents mixing both languages |
| English only | English-only documents |

---

## Supported File Types

| Input | Output |
|-------|--------|
| PNG, JPG, TIFF | TXT |
| PDF (multi-page) | Word (.docx) |
| | PDF |
| | EPUB (e-book) |

---

## Troubleshooting

**Mac says the app can't be opened because it is from an unidentified developer**
→ Right-click **TextLens OCR.app** and choose **Open**, then click **Open** in the dialog.

**A dialog appeared asking to install developer tools**
→ Click **Install**, wait for it to finish, then press **Enter** in the Terminal window to continue.

**"Could not connect to server" in the app**
→ Close the browser tab and double-click **TextLens OCR.app** again. Keep the Terminal window open while using the app.

**PDF processing is very slow**
→ This is normal for large files. A 400-page book may take 45–60 minutes. The app shows a live page counter and estimated time remaining. You can use your Mac normally while it runs.

**The app stopped working after a macOS update**
→ Double-click **TextLens OCR.app** again — it will detect the issue and re-run the installer automatically.

---

## How It Works

TextLens OCR uses [Tesseract](https://github.com/tesseract-ocr/tesseract), a free open-source OCR engine. Everything runs locally on your Mac — no data is sent anywhere.

---

## License

Free to use for personal use.
