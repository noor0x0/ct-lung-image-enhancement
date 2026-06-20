# CT Lung Image Enhancement

## Overview
This project focuses on enhancing lung CT images using digital image processing techniques.  
The goal is to improve the visibility of fine details, edges, and possible nodules in low-contrast or noisy CT images.

## Problem Definition
CT images may contain low contrast or noise, making it difficult to identify fine details such as nodules, lesions, and airway boundaries.  
This project applies several image enhancement techniques to improve visual clarity and support better analysis.

## Dataset
The project uses CT scan images from a Kaggle DICOM dataset.

## Techniques Used
- Histogram Equalization
- CLAHE (Contrast Limited Adaptive Histogram Equalization)
- Sobel Edge Enhancement
- HU Conversion and Windowing

## Why These Techniques?
### Histogram Equalization
Improves global contrast and makes low-contrast structures more visible.

### CLAHE
Enhances local contrast while limiting noise amplification, making it useful for medical images.

### Sobel Edge Enhancement
Highlights edges and boundaries between tissues, helping reveal lung structures more clearly.

### HU & Windowing
Uses Hounsfield Unit conversion and windowing to focus on meaningful intensity ranges in CT images.

## Technologies Used
- Python
- OpenCV
- NumPy
- Matplotlib
- Pydicom
- Digital Image Processing

## Summary
HE improves global low contrast.
CLAHE enhances local details.
Sobel highlights weak edges.
HU and windowing improve CT intensity interpretation.

## Author

Noor Mamoun
IT / AI Student
The Hashemite University
