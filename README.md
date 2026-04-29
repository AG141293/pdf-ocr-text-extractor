# pdf-ocr-text-extractor
Python OCR project to convert scanned PDF files into editable text using Tesseract, pdf2image, and PyTesseract.
# PDF OCR Text Extractor (Hindi + English)

## Overview
This project extracts text from scanned PDF documents using Optical Character Recognition (OCR) and converts them into editable text files.

It supports:
- English OCR
- Hindi OCR
- Multi-page PDF processing
- Automatic TXT output generation

## Features
✅ Upload scanned PDF files  
✅ Convert PDF pages into images  
✅ Extract text using Tesseract OCR  
✅ Hindi + English language support  
✅ Save extracted text as .txt file  
✅ Download output automatically

## Tech Stack
- Python
- Tesseract OCR
- PyTesseract
- pdf2image
- Pillow
- Google Colab

## Workflow
1. Install required dependencies
2. Upload scanned PDF
3. Convert each PDF page into images
4. Perform OCR on each page
5. Extract and combine text
6. Save extracted content into TXT file
7. Download generated output

## Installation
```bash
apt-get install tesseract-ocr tesseract-ocr-hin poppler-utils
pip install pytesseract pdf2image pillow
```

## Libraries Used
```python
import pytesseract
from pdf2image import convert_from_path
from google.colab import files
```

## OCR Languages Used
```python
lang="hin+eng"
```

Supports:
- Hindi
- English
- Mixed bilingual documents

## Example Use Cases
- Scanned document digitization
- Hindi document extraction
- OCR for government forms
- Old book/document text extraction
- Document preprocessing for NLP pipelines

## Output
Input:
Scanned PDF

Output:
Editable .txt file containing extracted text.

## Future Improvements
- Add image preprocessing for better OCR accuracy
- Support more regional languages
- Build Streamlit web app
- Export to CSV / JSON
