# Geometric Transformations Using OpenCV

## Aim
To develop a Python program using OpenCV to perform various geometric transformations on an image.

The transformations included in this project are:

- Image Translation
- Image Scaling (Resizing)
- Image Shearing
- Image Reflection (Flipping)
- Image Rotation

---

## Software Requirements

- Python 3.7
- Anaconda
- Jupyter Notebook / VS Code
- OpenCV (`cv2`)
- NumPy
- Matplotlib

---

## Description

Geometric transformations are image processing techniques used to modify the spatial orientation, size, position, and shape of an image. These operations are commonly used in computer vision, image augmentation, and preprocessing applications.

This project demonstrates the implementation of basic geometric transformations using OpenCV and Python.

---

## Algorithm

### Step 1
Import the required libraries:
- OpenCV
- NumPy
- Matplotlib

### Step 2
Read the input image in color mode.

---

## Transformations Performed

### 1. Image Translation
- Create a translation matrix
- Shift the image:
  - 50 pixels to the right
  - 80 pixels downward
- Apply the transformation using `cv2.warpAffine()`
- Display the original and translated images

---

### 2. Image Scaling
- Resize the image to:
  - 0.5× (downscale)
  - 2× (upscale)
- Use `cv2.resize()`
- Display original, downscaled, and upscaled images

---

### 3. Image Shearing
- Create transformation matrices for:
  - Horizontal shearing
  - Vertical shearing
- Apply transformations using `cv2.warpAffine()`
- Display the sheared images

---

### 4. Image Reflection
Perform image flipping using `cv2.flip()`:
- Horizontal reflection
- Vertical reflection
- Reflection across both axes

Display all reflected images.

---

### 5. Image Rotation
- Rotate the image by:
  - 45°
  - 90°
- Use:
  - `cv2.getRotationMatrix2D()`
  - `cv2.warpAffine()`
- Display the rotated images

---

## Output

### Image Translation
- Original Image
- Translated Image

### Image Scaling
- Original Image
- Downscaled Image
- Upscaled Image

### Image Shearing
- Original Image
- Horizontally Sheared Image
- Vertically Sheared Image

### Image Reflection
- Horizontally Flipped Image
- Vertically Flipped Image
- Both-Axis Flipped Image

### Image Rotation
- 45° Rotated Image
- 90° Rotated Image

---

## Result

Thus, various geometric transformations such as translation, scaling, shearing, reflection, and rotation were successfully performed using OpenCV. These transformations demonstrate how images can be spatially manipulated for different computer vision applications.

---

## Developed By

**Name:** udhaya prakash v 
**Register Number:** 212224240177
