# OCR
### `Optical Character Recognition`

- The electronic conversion of images of typed, handwritten or printed text into machine encoded text.
- From a scanned document, a photo of a document, subtitle text superimposed on an image.
- Extracting text from PDF and images (JPG, BMP, TIFF, GIF) and convert into editable Word, Excel and text output formats.


Download and install `tesseract` ocr engine.
[Tesseract Wiki](https://github.com/UB-Mannheim/tesseract/wiki)
```
https://digi.bib.uni-mannheim.de/tesseract/tesseract-ocr-w64-setup-v5.0.0-rc1.20211030.exe
```

Install libraries
```python
pip install opencv-contrib-python
pip install pytesseract
```

Import Libraries
```python
import cv2
import pytesseract

# Set path 
pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe'
```

