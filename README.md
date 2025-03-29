# Word-PDF Converter

This Python project allows you to convert Word documents (`.docx`) to PDFs and vice versa. It utilizes `python-docx`, `reportlab`, and `pdfplumber` to handle the conversions.

## Features
- Convert `.docx` files to `.pdf`
- Convert `.pdf` files to `.docx`

## Requirements
Make sure you have the following Python packages installed:
```bash
pip install python-docx reportlab pdfplumber
```

## Usage
### Convert Word to PDF
```python
from word_pdf_converter import word_to_pdf
word_to_pdf("sample.docx", "output.pdf")
```

### Convert PDF to Word
```python
from word_pdf_converter import pdf_to_word
pdf_to_word("output.pdf", "converted.docx")
```



