This project uses **YOLOv8 (Ultralytics)** to detect potholes in road images. The trained model can identify potholes and visualize them with bounding boxes.  

## 🚀 Features  
- Detect potholes in static images  
- Visualize results with bounding boxes  
- Easy to run on **Google Colab** or **local system**  
- Extendable to videos and real-time detection  


## 📂 Project Structure  
├── README.md <- Project documentation
├── requirements.txt <- Required dependencies
├── best.pt <- Trained YOLOv8 weights (add your own)
├── pothole_detection.ipynb<- Colab/Notebook for testing
├── detect.py <- Script to run detection
└── samples/ <- Example input/output images

## 📦 Requirements
-Python 3.8+
-PyTorch
-Ultralytics YOLOv8
-OpenCV
-Matplotlib

## 🙌 Acknowledgements
Ultralytics YOLOv8
OpenCV for image processing
