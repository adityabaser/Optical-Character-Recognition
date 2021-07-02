# Optical-Character-Recognition
Building out a Flask application having OCR capabilities to detect text from images using PyTesseract. 

PyTesseract is an optical character recognition package developed by Google to recognize and read the text embedded in images. We also build a Flask Application to make it more user friendly for the user to use the product. 

We are going to test out printed and a handwritten images and access the extracted text. 

## Installation of required modules

For PyTesseract, one need to first download the extension from the given link here, https://github.com/UB-Mannheim/tesseract/wiki

Specify the path,
pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe'

* pip install pytesseract
* pip install pipenv
* pip install Pillow
* pip install Flask

## Flask Application

### Test Image 

![Test Image](https://github.com/adityabaser/Optical-Character-Recognition/blob/main/static/uploads/ocr_image1.PNG)

### User Interface for the Flask Application 

![User Interface](https://github.com/adityabaser/Optical-Character-Recognition/blob/main/Screenshots/Flask%20Application%20Interface%20Screenshot.PNG)

### Result 

![Result Screenshot](https://github.com/adityabaser/Optical-Character-Recognition/blob/main/Screenshots/OCR%20Result%20Screenshot.PNG)


