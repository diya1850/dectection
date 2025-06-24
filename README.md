
# 🚀 YOLOv8 Object Detection – Google Colab Implementation

This project demonstrates how to implement object detection using the YOLOv8 model from Ultralytics on a Google Colab notebook. It walks through the complete pipeline from installing dependencies to running predictions and visualizing results.

## 📒 Project Overview

YOLOv8 (You Only Look Once version 8) is a state-of-the-art, real-time object detection model by Ultralytics. This notebook performs:

1. Installing Ultralytics package
2. Importing the YOLO module and checking the setup
3. Uploading and testing on a custom image
4. Loading the pre-trained YOLOv8n model
5. Running object detection and displaying the result
6. Printing class names, confidence scores, and bounding box details

---

## 📂 Output

* 🔍 The output (predicted image) is saved in:
  `/content/runs/detect/predict/`
* 📥 You can download it using:

  ```python
  from google.colab import files
  files.download('runs/detect/predict/' + os.path.basename(image_path))
  ```

---

## 🛠️ Technologies Used

* Google Colab
* Python
* Ultralytics YOLOv8
* IPython display tools

---

## 🧠 Steps to Run

1. Open the [Google Colab notebook](https://colab.research.google.com/)
2. Run all cells step by step
3. Upload your test image when prompted
4. View the detected objects and download the result


