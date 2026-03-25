Traffic Sign Detection - Python + YOLOv8

Description

This application is a Deep Learning system developed in Python that allows users to identify and classify traffic signs from images or video streams automatically. The project utilizes the YOLOv8 architecture to ensure rapid and precise detection, serving as an essential solution for road safety and autonomous vehicles.

Authors & Date

Authors: Ungureanu Andrei and Tudora Ionuț

Date: 18.12.2025

Key Features

Object Localization: Automatic identification of signs through the use of bounding boxes.

Automatic Classification: Assigning specific labels to detected signs (e.g., "Speed Limit 50", "Stop", "Traffic Light").

Data Storage: Automatic saving of predictions and coordinates in structured formats like .txt or .csv files.

Tech Stack

Ultralytics (YOLOv8): Used for the detection model architecture.

OpenCV: Used for image preprocessing and real-time visualization.

YAML: Used for dataset configuration (classes and access paths).

Installation & Setup

Check Python: Ensure you have Python installed.

python --version


Download Project: Clone the repository or download the source files.

Install Dependencies: Run the following command:

pip install ultralytics opencv-python


Navigation: Open a terminal and navigate to the project directory.

Usage

Execution: Run the application:

python main.py


Input Source: Provide the path to a traffic image (e.g., test_traffic.jpg).

Settings: Select the desired confidence threshold (e.g., 0.5).

Visualization: The results will appear in a new window, marking all identified signs.

Future Extensions

Database Integration: Saving detected data into an SQLite database for history management.

Category Filtering: Adding options to filter for specific signs (e.g., speed limits only).

Export Reports: Capability to export detections from a session into a detailed PDF file.

Advanced UI: Transitioning to a modern graphical interface using Custom Tkinter or PyQt5.
