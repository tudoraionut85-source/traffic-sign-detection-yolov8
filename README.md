Traffic Sign Detection - Python + YOLOv8
Description
This application is a Deep Learning system developed in Python that allows users to identify and classify traffic signs from images or video streams automatically. The project utilizes the YOLOv8 architecture to ensure rapid and precise detection, serving as an essential solution for road safety and autonomous vehicles.

Authors & Date
Authors: Ungureanu Andrei and Tudora Ionuț

Date: December 18, 2025

Key Features
Object Localization: Automatic identification of signs through bounding boxes.

Automatic Classification: Assignment of specific labels to detected signs (e.g., "Speed Limit 50", "Stop", "Traffic Light").

Data Storage: Automatic saving of predictions and sign coordinates in structured formats like .txt or .csv files.

Technologies Used
Ultralytics (YOLOv8): For the detection model architecture.

OpenCV: For image preprocessing and real-time visualization.

YAML: For dataset configuration (classes and paths).

Installation & Setup
Check Python: Ensure Python is installed:

Bash
python --version
Download Project: Clone the repository or download the source files.

Install Dependencies:

Bash
pip install ultralytics opencv-python
Navigation: Open a terminal and navigate to the project directory.

Usage
Execution:

Bash
python main.py
Input Source: Provide the path to a traffic image (e.g., test_traffic.jpg).

Settings: Select a confidence threshold (e.g., 0.5).

Visualization: View results in the pop-up window marking all identified signs.

Future Extensions
Database Integration: Saving detected data into SQLite for history management.

Category Filtering: Options to filter for specific signs (e.g., speed limits only).

Export Reports: Capability to export detections into a detailed PDF file.

Advanced Design: Transitioning to a GUI using Custom Tkinter or PyQt5.
