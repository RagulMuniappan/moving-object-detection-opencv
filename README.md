## Moving Object Detection using OpenCV

A real-time moving object detection system that identifies motion through a webcam feed using OpenCV and background frame differencing.

---

### About the Project

This project demonstrates a basic computer vision–based moving object detection system.  
It captures live video from a webcam, compares each frame with a reference frame, and detects motion by identifying changes between frames. Detected moving objects are highlighted with bounding boxes in real time.

---

### Features

- Real-time motion detection using webcam  
- Background frame differencing technique  
- Contour-based moving object detection  
- Bounding box visualization for detected motion  
- Lightweight and fast execution  

---

### Technologies Used

- Python  
- OpenCV  
- NumPy  
- Imutils  

---

### How to Run

1. Run the moving object detection script:
   ```bash
   python main.py
2. Press r to stop the camera feed and exit the program.

---

### Working Principle

- Capture the first frame as background reference  
- Convert frames to grayscale and apply Gaussian blur  
- Compute absolute difference between frames  
- Apply thresholding and dilation  
- Detect contours representing moving objects  

---

### Applications

- Motion detection systems  
- Security and surveillance  
- Smart camera systems  
- Smart camera applications  
- Learning computer vision fundamentals  

---

### Output

- Real-time detection of moving objects  
- Moving objects highlighted with bounding boxes  

---
