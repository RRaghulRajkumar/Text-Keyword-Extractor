# Text-Keyword-Extractor 📃 


## Objective
Develop a system that can extract text from images and PDF files and then identify and rank important keywords within the extracted text.


## Technologies Used

The project utilizes the following Python and NLP technologies:

### Tesseract OCR
- **Description**: Tesseract OCR (Optical Character Recognition) is an open-source engine for extracting text from images. It's widely used for text extraction from various image formats.
- **Usage in the Project**: Tesseract OCR is used to extract text from images provided as input.

### Pillow (PIL)
- **Description**: Pillow (PIL - Python Imaging Library) is a Python imaging library that adds image processing capabilities to your Python interpreter. It is used for opening, manipulating, and saving various image file formats.
- **Usage in the Project**: Pillow is likely used for image preprocessing and handling in the text extraction process.

### PyMuPDF (MuPDF)
- **Description**: PyMuPDF is a Python binding for MuPDF, a lightweight PDF and XPS viewer. It allows you to extract text and perform various operations on PDF documents.
- **Usage in the Project**: PyMuPDF is utilized for extracting text from PDF files provided as input.

### Flask
- **Description**: Flask is a lightweight and flexible micro web framework for Python. It is used to create web applications, including APIs, for serving and interacting with the system.
- **Usage in the Project**: Flask is likely used to create a web interface for users to upload images and PDF files and receive extracted text and keyword rankings.

### spaCy
- **Description**: spaCy is an open-source natural language processing library for Python. It provides tools for various NLP tasks, including tokenization, part-of-speech tagging, named entity recognition, and more.
- **Usage in the Project**: spaCy can be used for NLP analysis, including identifying and ranking important keywords within the extracted text. It helps in text processing and linguistic analysis.

These technologies and libraries collectively contribute to the functionality of the system, allowing it to extract text from images and PDFs and perform NLP-based keyword ranking. Make sure to install and configure these libraries as part of your project setup.

## Project Screenshots 
![alt text](https://github.com/RRaghulRajkumar/Text-Keyword-Extractor/blob/master/demo/image1.png)

### File Selection
![alt text](https://github.com/RRaghulRajkumar/Text-Keyword-Extractor/blob/master/demo/image2.png)

### Input File
![alt text](https://github.com/RRaghulRajkumar/Text-Keyword-Extractor/blob/master/demo/images.png)

### Final Output
![alt text](https://github.com/RRaghulRajkumar/Text-Keyword-Extractor/blob/master/demo/image3.png)

![alt text](https://github.com/RRaghulRajkumar/Text-Keyword-Extractor/blob/master/demo/image4.png)

### Project Demo Video
[![Watch the video](https://github.com/RRaghulRajkumar/Text-Keyword-Extractor/blob/master/demo/textgenerator.mp4)]



