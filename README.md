# Real-Time Sketch Generation using Adaptive Thresholding  

## 📌 Project Overview  
This Python project demonstrates **real-time sketch generation** from a webcam feed using **OpenCV**. The program captures video frames, processes them using image processing techniques (e.g., grayscale conversion, Gaussian blur, and Canny edge detection), and generates a sketch-like output.  

**Features**:  
- Real-time edge detection using **Canny Edge Detection**.  
- **Adaptive Thresholding** applied to edges for sketch-like visuals.  
- Displays live webcam feed with processed sketch output.  
- Press **'q'** to exit the application.  

---

## 🚀 Key Features  
1. **Grayscale Conversion**:  
   - Converts frames to grayscale using `cv2.cvtColor()`, reducing complexity and focusing on intensity.  
2. **Gaussian Blur**:  
   - Applies a Gaussian filter to reduce noise and improve edge detection.  
3. **Canny Edge Detection**:  
   - Detects edges using `cv2.Canny()` based on intensity gradients.  
4. **Adaptive Thresholding**:  
   - Converts edges into a binary image using `cv2.adaptiveThreshold()` for enhanced sketch effects.  

---

## 🔍 How It Works  
1. **Grayscale Conversion**:  
   - Each frame is converted to grayscale to simplify processing.  
2. **Gaussian Blur**:  
   - The grayscale image is blurred to reduce noise and smooth edges.  
3. **Canny Edge Detection**:  
   - Edges are detected using intensity gradients, highlighting key features.  
4. **Adaptive Thresholding**:  
   - Edges are thresholded to create a binary sketch-like output.  

---

## 🛠 Usage  
### Dependencies  
- Python 3.8+  
- Libraries: `opencv-python`

---

## 📄 License  
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
