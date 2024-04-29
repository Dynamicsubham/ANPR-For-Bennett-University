# Vehicle-Plate-Recognition-System-For-Bennett-University
This project aims to develop a vehicle plate detection system specifically designed for Bennett University. The system utilizes YOLOv8, a state-of-the-art object detection model, to detect vehicle license plates in images. Additionally, it incorporates EasyOCR for the recognition of alphanumeric characters on the detected license plates.

# Files
    yolov8s.pt: Pretrained YOLOv8 model weights.
    runs/: Directory containing test runs.
    runs/train/weights: Model trained on a dataset of 300 images using YOLOv8.
    detect_and_recognition.py: Python script for detecting and recognizing vehicle license plates using the trained model and EasyOCR.
    web_app/: Directory containing the integrated web application.
    web_app/main.py: Python script to start the web application and server using Streamlit.

You can use "Yolo8 Training Commands in CLI.text" for reference as I didnt train the model in jupyter notebook, I trained it in my terminal using CLI commands by refering Yolov8 Documentation. Although I have given up a IPYNB file just for the reference of the codes I ran in my terminal.

# Usage:

Pretrained Model: The yolov8s.pt file contains the pretrained YOLOv8 model weights. Ensure this file is present in the project directory.

Trained Model: The runs/train/weights/best.pt directory contains the model trained on web scraped dataset. Make sure this directory is available.

Detection and Recognition: Use the detect_and_recognition.py script to detect and recognize vehicle license plates. This script integrates the best.pt model inside runs folder for detection and EasyOCR for character recognition.

Web Application: The web_app/ directory contains the integrated web application. Run the main.py script inside this directory to start the web application and server using Streamlit.



# Note:

This project is a prototype and was developed within a span of two months. While it demonstrates the feasibility of vehicle plate detection for Bennett University, further refinement and additional resources would be necessary for a full-fledged deployment.
