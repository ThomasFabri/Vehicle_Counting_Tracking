Vehicle Counting System using YOLOv11
This project implements a real-time vehicle counting system leveraging YOLOv11, a state-of-the-art object detection model, to detect and track vehicles on a road. The application processes video streams or recorded footage, identifies vehicles crossing a predefined counting line, and keeps an accurate tally of the total number of vehicles passing through.

Key Features
Real-Time Detection: Utilizes YOLOv11 for fast and accurate detection of vehicles such as cars, trucks, buses, and motorcycles.

Customizable Counting Line: Allows you to define a virtual line or region of interest (ROI) for counting vehicles.

Object Tracking: Integrates a tracking mechanism (e.g., using object IDs) to ensure each vehicle is counted only once.

Performance Optimized: Capable of processing live video streams or pre-recorded videos with minimal latency.

Flexible Input Sources: Supports video files, IP cameras, or live webcams.

How It Works
Frame Capture: The system reads frames from the video source.

Object Detection: Each frame is analyzed using YOLOv11 to detect vehicles and obtain bounding boxes.

Line Crossing Logic: The script monitors the position of detected vehicles and checks if they cross the predefined counting line.

Counting & Display: Updates and displays the total vehicle count in real-time on the video output.

Use Cases
Traffic Monitoring: Count and classify vehicles for traffic flow analysis.

Urban Planning: Collect data for infrastructure improvements.

Toll Systems: Automate vehicle counting for toll booths.

Technologies Used
Python 3.x

YOLOv11 (Ultralytics)

OpenCV for image processing and video handling.

NumPy for numerical operations.
