# AadhaarShield: Aadhaar Card Masking System

## Overview

AadhaarShield is a web-based application designed to mask sensitive Aadhaar numbers in images, ensuring privacy and security. Utilizing Optical Character Recognition (OCR) with EasyOCR and image processing with OpenCV, the system allows users to upload Aadhaar card images and automatically masks the first eight digits.

## Features

- User-friendly interface for uploading Aadhaar card images.
- Automatic detection of Aadhaar numbers using EasyOCR.
- Masking of the detected Aadhaar numbers with OpenCV.
- Option for users to download the masked image.

## System Architecture

### Components

- **Frontend**: Built with HTML/CSS and JavaScript for the user interface (UI).
- **Backend**: Flask API for handling image uploads and processing.
- **Libraries Used**:
  - **EasyOCR**: For extracting text from images.
  - **OpenCV**: For processing images and applying masks.

### Workflow

1. User uploads an Aadhaar card image through the web form.
2. The backend detects the Aadhaar number and applies a mask.
3. The processed image is returned to the user for viewing and downloading.

## Implementation Details

### Frontend Development

The HTML form provides an interface for uploading Aadhaar card images and displaying the masked results.

### Backend Development

The Flask API processes image uploads, detects Aadhaar numbers, and applies masks.

## Testing and Validation

- **Upload Tests**: Verified accurate number detection and masking with various Aadhaar card images.
- **Validation**: Ensured usability across devices and browsers.

## Deployment

### Deployment Options

- Local Deployment: Run locally for development and testing.
- Cloud Deployment: Deploy on platforms like Heroku, AWS, or Google Cloud.

### Steps for Deployment

1. Prepare the application for deployment (using Gunicorn for production).
2. Select a hosting platform and configure the environment.
3. Deploy the application and perform post-deployment testing.

## Conclusion

AadhaarShield provides an effective solution for masking Aadhaar numbers in images, ensuring privacy and ease of use. Future enhancements may include security features and multilingual support.

## Contact Information

**Name**: Asmajahan Karkal  
**Email**: asmajahankarkal@gmail.com  
**LinkedIn**: [Asmajahan Karkal](https://www.linkedin.com/in/asmajahan-karkal)
