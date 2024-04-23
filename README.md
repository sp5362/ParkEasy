# ParkEasy-Park_space_detection

Description of the hack : 

Our project simplifies parking with real-time updates on space availability. Users scan a QR code upon entry to see open spots instantly. Exiting, they can pay with cash or cashless methods, reducing wait times and congestion.

Features:

Instant Space Availability: View open spots upon QR scan.

Convenient Payments: Pay with cash or cashless methods at exit.

Implementation:

YOLOv8 Algorithm: Powers real-time space detection.

Live Camera Feeds Integration: Seamless updates from cameras.

Intuitive User Interface: Simple, visual display of available spaces.

Benefits:

Efficiency Boost: Streamlines parking, saving time.

Traffic Reduction: Guides users to open spots, easing congestion.

No Wait Times: Smooth exits without long lines.

Our goal is to make parking hassle-free, efficient, and user-friendly for everyone.

Tech stack used :

Machine Learning
Deep Learning
Computer Vision
YOLOv8
HTML/CSS
Python

Installation steps:

Back-end python:

First download the 3 files (finalparking.ipynb, parkingspace.zip and coco.txt)

Extract the files fromt the parkingspace.zip -> We will get a video file

Either keep all the files in the same folder . If you are not able to do it, copy the path of the parking1.mp4 and paste the path in the 19th line instead of 'parking1.mp4'

Make sure that all the libraries are downloaded if not you can download it by using the following commands:

pip install opencv-python

pip install pandas

pip install ultralytics

Libraries and dependencies required for the project :

numpy
pandas
opencv
cv2
ultralytics
time
