# 🧠 Computer Vision Shape Detection

A computer vision project implementing classical image processing techniques for **shape detection** using OpenCV.

The system is divided into two main modules:
-  Edge & Shape Detection Module  
-  Active Contour Segmentation Module  

---

# 🔍 Mode 1: Edge & Shape Detection

Detecting geometric structures and extracting shapes from images.

## ✨ Features

### 🔹 Edge Detection Engine
- Detects edges using **Canny Edge Detector**
- Highlights object boundaries in images
<img width="1368" height="930" alt="image" src="https://github.com/user-attachments/assets/9f71085e-fbd5-4fc1-952e-a5ac85309edc" />

---

### 📏 Line Detection
- Uses **Hough Line Transform**
- Detects straight lines in different orientations
<img width="1372" height="928" alt="image" src="https://github.com/user-attachments/assets/5e10b26b-6074-4bbd-a416-3f382e83314f" />

---

### ⚪ Circle Detection
- Uses **Hough Circle Transform**
<img width="1372" height="938" alt="image" src="https://github.com/user-attachments/assets/73d43a0c-446a-4fe4-97f5-77ad67984838" />

---

### 🟣 Ellipse Detection
- Fits ellipses from detected contours
- Handles noisy or partially visible shapes
<img width="1371" height="937" alt="image" src="https://github.com/user-attachments/assets/f706b245-f20f-44a3-a0fb-df55c41984a2" />

---

#  Mode 2: Active Contour (Snake Segmentation)

This mode focuses on object segmentation using contour evolution techniques.

---

## ✨ Features

### 🎯 Active Contour Initialization
- Initializes contour around target object
- Defines starting boundary for segmentation

---

### 🔄 Snake Evolution (Greedy Algorithm)
- Iteratively evolves contour
- Converts final contour into chain code format
- Computes **Perimeter** of contour
- Computes **Area inside segmented object**
<img width="1376" height="938" alt="image" src="https://github.com/user-attachments/assets/11175426-57ec-46e5-b759-36328adb36ca" />

---

## 🛠️ Tech Stack

- Python   
- OpenCV  
- NumPy  
- Matplotlib  

---

## 👥 Contributors
|  [Mostafa Ayman](https://github.com/mostafaayman646) | [Amr](https://github.com/Amr20545) | [Nada Hesham](https://github.com/Nada-Hesham249)  | [Samar Hatem](https://github.com/samarhatem0405) | [Nada Hassan](https://github.com/Nadahassan147)  |
|-------------------------------|---------------------------|-----------------------------------|-------------------------------|-------------------------------|
