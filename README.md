# Roshni-Banerjee-Bajaj-Finserv-Health-Data-Science-Q2
Problem Statement: Develop a scalable and accurate solution to process lab reports with the objective of extracting all lab test names, their corresponding values, and reference ranges.

Lab Report Extraction API
This project is a Python-based FastAPI service developed to extract structured lab test data from lab report images. The solution processes an image of a lab report and returns test names, corresponding values, reference ranges, and whether the values fall outside the normal range.

Problem Statement
Build a scalable and accurate system that:

Extracts lab test names, values, and reference ranges from lab report images.

Determines if each test result is within or outside the normal range.

Returns the extracted data in a structured JSON format through a RESTful API endpoint.

Features
Accepts lab report images through a POST endpoint.

Extracts structured information using custom OCR and parsing logic.

Identifies out-of-range values using the extracted reference range.

Returns a JSON response with all lab tests and their metadata.

Technologies Used
Python

FastAPI – Web framework for the API

Tesseract OCR – Optical character recognition

OpenCV / PIL – Image preprocessing

Regex / Custom parsing logic – Text structure analysis


![image](https://github.com/user-attachments/assets/0a565720-ffa6-4e19-8600-434b10951170)

