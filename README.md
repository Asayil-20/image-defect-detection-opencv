# 🧠 Image Defect Detection using OpenCV

This project detects visual damage in any image using computer vision techniques.  
It highlights damaged areas (like cracks, burns, or breaks) and calculates the percentage of the image affected.

## 📌 What It Does
- Uploads any image with visible damage
- Applies Canny edge detection + contour detection
- Marks damaged regions with red rectangles
- Calculates:
  - Number of defects
  - Total defect area (in pixels)
  - Damage percentage relative to image size

## 📷 Example Use Cases
- Burned cables
- Cracked walls or screens
- Damaged equipment or tools

## ✅ Sample Output
- Defects found: **12**  
- Defect area: **3520 px²**  
- Damage percent: **4.65%**

Annotated image shows red boxes around all defects.

## 🚀 How to Run
1. Install required libraries:
pip install -r requirements.txt
2. Open the notebook:
image-defect-detection-using-opencv.ipynb
3. Upload your image and run the analysis cells.

## 📄 Files
- `image-defect-detection-using-opencv.ipynb`: Main notebook
- `requirements.txt`: Required Python packages
- `example-output.png`: Sample annotated result
