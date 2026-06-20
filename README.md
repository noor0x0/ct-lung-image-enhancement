# CT Lung Image Enhancement

## Overview
This project focuses on enhancing lung CT images using digital image processing techniques.  
The goal is to improve the visibility of fine details, edges, and possible nodules in low-contrast or noisy CT images.

## Problem Definition
CT images may contain low contrast or noise, making it difficult to identify fine details such as nodules, lesions, and airway boundaries.  
This project applies several image enhancement techniques to improve visual clarity and support better analysis.

## Dataset
The dataset used in this project is a public CT scan dataset from Kaggle.

## Techniques Used
- Histogram Equalization
- CLAHE (Contrast Limited Adaptive Histogram Equalization)
- Sobel Edge Enhancement
- HU Conversion and Windowing

## Technologies Used
- Python
- NumPy
- Matplotlib
- OpenCV
- Pydicom
- Digital Image Processing

## Project Structure
```text
ct-lung-image-enhancement/
├── README.md
├── ct_lung_image_enhancement.ipynb
├── CT_Lung_Image_Enhancement_Presentation.pptx
└── requirements.txt
```
## Summary
Histogram Equalization improves global contrast.
CLAHE enhances local details while limiting noise amplification.
Sobel highlights edges and tissue boundaries.
HU and windowing help focus on meaningful CT intensity ranges.
Author

## Author

Noor Mamoun
IT / AI Student
The Hashemite University
