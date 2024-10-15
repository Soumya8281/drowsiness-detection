driver-drowsiness-detection
A deep learning project to detect driver drowsiness using computer webcam. Features real-time monitoring and alert system.

📝 Overview
Execution Order
-Environment Setup

pip install -r requirements.txt
-Data Preparation

Using Dataset in roboflow. you can also downloading in here -> Dataset Link

Following below command prompt to proceed with training

yolo task=detect mode=train model=yolov8s.pt data={./data}/data.yaml epochs=100 imgsz=640
-Execution

You can skip the first two steps by downloading the best.pt file that we previously uploaded.

Please execute the code within a virtual environment where the requirements have been installed.

python main.py
