
# Text Extraction from Images Using Tesseract OCR



This project implements Optical Character Recognition (OCR) using Tesseract and Python to extract text from images. The extracted text is saved into a text file for easy access and analysis.



## Features

- Extracts text from images using Tesseract OCR.
- Saves the extracted text into a `.txt` file for easy access.
- Supports various image formats (e.g., JPG, PNG).

## Installation

1. Install Tesseract OCR:
   ```bash
   sudo apt install tesseract-ocr
   ```

2. Install the required Python package:
   ```bash
   pip install pytesseract Pillow
   ```

## Usage

1. Place the image file you want to process in the project directory.
2. Modify the filename in the script if necessary:
   ```python
   info = recText('data.jpg')
   ```

3. Run the script:
   ```bash
   python ocr_script.py
   ```

4. The extracted text will be saved in `result.txt`.

## Requirements

- Python 3.x
- Tesseract OCR
- pytesseract
- Pillow

## How It Works

1. The script loads the specified image using the Pillow library.
2. Tesseract OCR processes the image to extract text.
3. The extracted text is written to `result.txt`.

## Results

After running the script, the extracted text will be available in `result.txt`. Open this file to view the recognized text.
