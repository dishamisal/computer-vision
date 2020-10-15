# computer-vision
Computer Vision and OpenCV problems in Python

## Problem Statement
Read text on product images.
The input consists of a few images of products on top of which there is information related to them like name, ingredients, etc.
The goal is to read this text on the images.

## Approach:
Python has an OCR tool called pytesseract to read text on images. It was used to print the text from the images in jupyter notebook.
Python Image Library (PIL) is an image library which can open, manupulate and save different image formats. The sample images in this code were of .jpeg format.
PIL while doing image processing assumes the order of colour of images to be RGB.
Tesseract, after extracting text from the images, also gave "\n" characters which are not needed in the final output. These were removed and a cleaned text is displayed.

