# OpenCV Image Thresholding

This project demonstrates various image thresholding techniques using Python and OpenCV. Thresholding is a fundamental image segmentation technique used to separate objects from the background by converting grayscale images into binary images.

---

## Features

- Load and display an input image
- Convert image to grayscale
- Apply Simple Binary Thresholding
- Apply Binary Inverse Thresholding
- Apply Truncation Thresholding
- Apply To-Zero Thresholding
- Apply Adaptive Thresholding
- Apply Otsu’s Thresholding
- Display all thresholding outputs for comparison

---

## Technologies Used

- Python 3.7+
- OpenCV (`cv2`)
- NumPy
- Matplotlib
- Jupyter Notebook / VS Code

---

## Thresholding Techniques

### Binary Thresholding
Converts pixel values above a threshold to white and below the threshold to black.

### Binary Inverse Thresholding
Performs the inverse operation of binary thresholding.

### Truncation Thresholding
Pixel values above the threshold are truncated to the threshold value.

### To-Zero Thresholding
Retains pixel values above the threshold and sets others to zero.

### Adaptive Thresholding
Calculates threshold values dynamically for smaller image regions.

### Otsu’s Thresholding
Automatically determines the optimal threshold value for image segmentation.

---

## Algorithm

1. Import required libraries
2. Read the input image using OpenCV
3. Convert the image to grayscale
4. Apply image smoothing if required
5. Perform Binary Thresholding
6. Perform Binary Inverse Thresholding
7. Perform Truncation Thresholding
8. Perform To-Zero Thresholding
9. Apply Adaptive Thresholding
10. Apply Otsu’s Thresholding
11. Display all results using Matplotlib
---
## Applications

- Image Segmentation
- Document Processing
- Medical Imaging
- Object Detection
- OCR Systems
- Computer Vision Applications

---

## Result

The implementation successfully demonstrates multiple image thresholding techniques using OpenCV. These methods help in image segmentation, feature extraction, and object isolation for computer vision and image processing applications.

---


## License

This project is open-source and available under the MIT License.
