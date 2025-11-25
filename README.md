Multilingual Image-to-Speech OCR System

This project implements an image-based text extraction and speech conversion system using Python.
It captures an image through a Raspberry Pi camera, performs OCR using Tesseract, and converts the extracted text into speech using Google Text-to-Speech (gTTS).
The system supports four languages: English, Tamil, Telugu, and Hindi.

Features

Real-time image capture using libcamera-still

Grayscale preprocessing with OpenCV for improved OCR accuracy

Text extraction using Tesseract OCR

Text-to-speech conversion using gTTS

Multilingual support (eng, tam, tel, hin)

Error handling for camera issues and blurry images

Technologies Used

Python

OpenCV

Tesseract OCR via pytesseract

gTTS for speech synthesis

mpg321 for audio playback

Raspberry Pi Camera (or compatible module)

Usage

Run the script:

python3 main.py


Select your preferred language when prompted.

The system captures an image, extracts text, and reads it aloud.

The extracted text is also printed to the terminal.

Installation Requirements

Install necessary packages:

sudo apt install tesseract-ocr libtesseract-dev mpg321
pip install opencv-python pytesseract gTTS


Install additional OCR languages:

sudo apt install tesseract-ocr-tam tesseract-ocr-tel tesseract-ocr-hin

Project Structure
project/
│── Smart reader.ipynb
│── README.md


Author

Developed as a Python-based multilingual OCR and text-to-speech system with real-time image acquisition.
