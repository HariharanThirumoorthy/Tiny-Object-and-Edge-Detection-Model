# Tiny-Object-and-Edge-Detection-Model
YOLO-based deep learning model for detecting tiny objects and edges in complex images using OpenCV and Canny filters.

## 🔧 Technologies Used
- Python
- YOLOv4
- OpenCV
- TensorFlow
- Canny Edge Detection

## 📌 Features
- High-accuracy object detection on small-scale items
- Enhanced edge recognition using Canny filters
- Image annotation and preprocessing pipeline

## 🚀 How to Run
1. Clone the repository
2. Set up the virtual environment:
   ```bash
   pip install -r requirements.txt
Set up the virtual environment

bash
Copy
pip install -r requirements.txt
Download YOLOv4 weights
Download the pre-trained YOLOv4 weights from the official site or darknet GitHub and place them in the weights/ directory.

Run detection on an image

bash
Copy
python detect.py --image path/to/image.jpg
Run edge detection

bash
Copy
python edge_detect.py --image path/to/image.jpg
📷 Demo
Tiny Object Detection	Edge Detection
🗂 Project Structure
csharp
Copy
tiny-object-detector/
├── detect.py
├── edge_detect.py
├── yolov4.cfg
├── weights/
│   └── yolov4.weights
├── images/
├── utils/
├── requirements.txt
└── README.md
📄 License
This project is licensed under the MIT License – feel free to use, share, and contribute!

🙌 Acknowledgements
YOLO by Alexey Bochkovskiy


