# TEXT DETECTION USING PYTHON
The following repo contains the code and requrired packages to detect text from images using python.
Project has been done using PyTesseract and OpenCV modules and run on Python3.
## PyTesseract:
Pytesseract is a Python library that provides an interface to the Tesseract optical character recognition (OCR) engine. OCR is a technology used to recognize and extract text from images, scanned documents or other visual media.

Follow this link to install Tesseract_OCR and add to PATH before running: [Tesseract Install](https://builtin.com/articles/python-tesseract) .
Go to cmd and type: ``` pip install pytesseract ``` .

To verify if pytesseract has been installed correctly : ```tesseract --version ``` .

## OpenCV:
OpenCV (Open Source Computer Vision Library) is an open source computer vision and machine learning software library.

Mainly used for image pre-processing before pushing to PyTesseract.

To install OpenCV, open cmd and type : ``` pip install opencv-python```

### NOTE:
install requests package if ypu havent already using: ``` pip install requests```.

This is used to access images from the repo.
