# File2PDF

Convert documents, images and text files to PDF with one click.
A lightweight Windows app — no installation, no setup.

## Download

1. Open **File2PDF.exe** in the file list above.
2. Click the **Download** button to save it (about 22 MB).
3. Double-click the downloaded **File2PDF.exe** to run it.

> **SmartScreen note:** the executable is unsigned, so Windows may show
> "Windows protected your PC". Click **More info → Run anyway** to start the app.

## How to use

1. Click **Choose file** and pick the file you want to convert.
2. Click **Save as...** to choose where the PDF is saved.
3. Click **Convert** — the status bar shows the result and the final file size.

## Supported input types

| Type | Extensions |
|---|---|
| Word | `.docx` |
| Excel | `.xlsx` |
| PowerPoint | `.pptx` |
| CSV | `.csv` |
| Images | `.png`, `.jpg`, `.jpeg` |
| Plain text | `.txt` |

Word, Excel and PowerPoint files are converted through Microsoft Office
automation, with an automatic LibreOffice fallback if Office isn't installed.
Images and text files need nothing extra.

Every PDF also goes through a **lossless compression pass**, keeping the
output as small as possible without quality loss.

## Requirements

- Windows 10 or 11
- Microsoft Office or LibreOffice (only needed for Office document types)
- Nothing else — the app is a self-contained executable; no Python required

## License

Released under the [MIT License](LICENSE).
