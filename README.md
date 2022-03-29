# Simple_OCR
Simple OCR template with using Python and Python Libraries

# Setup

--> If you are using Windows client, go to link and download Tesseract-OCR https://github.com/UB-Mannheim/tesseract/wiki.

--> Make sure PILLOW is installed for the photo library. https://pillow.readthedocs.io/en/stable/installation.html

--> If you don't have tesseract executable in your PATH, include the following:
pytesseract.pytesseract.tesseract_cmd = 'C:/Program Files/Tesseract-OCR/tesseract.exe'

# Different Languages

If you are going to OCR in different languages, be sure to download "tesseract data".
You can download languages -> https://github.com/tesseract-ocr/tessdata & C:\Program Files\Tesseract-OCR\tessdata paste it!
