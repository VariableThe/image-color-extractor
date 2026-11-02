# Image Color Extractor & Masker

A desktop GUI utility written in Python that allows you to extract specific colors from any image with adjustable tolerance and save transparent RGBA cutouts.

## ✨ Features

- **Interactive File Selection**: Easily pick any standard image file (`PNG`, `JPG`, `JPEG`, `BMP`, `WEBP`) using native file dialogs.
- **Visual Color Picker**: Select the exact target RGB color to isolate using a visual color chooser dialog.
- **Customizable Tolerance**: Set Euclidean color distance tolerance (0-255) to capture exact shades or broad color ranges.
- **Transparent Output**: Automatically masks out unselected background pixels to transparent RGBA and saves directly to PNG.

## 🛠 Prerequisites

Make sure you have Python 3 installed along with `tkinter` (included with standard Python installations on macOS and Windows).

Install required dependencies:

```bash
pip install -r requirements.txt
```

## 🚀 Usage

Run the tool from your terminal:

```bash
python3 extract_color.py
```

### Workflow steps:
1. **Select Image**: A file chooser dialog pops up to pick your input image.
2. **Pick Color**: Use the interactive color picker dialog to choose the target color you want to keep.
3. **Set Tolerance**: Enter a numeric distance tolerance between `0` (exact match only) and `255` (default is `30`).
4. **Save Cutout**: Pick a destination filename to save the transparent PNG cutout.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
