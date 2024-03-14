# Live Car Parking Space Detection
This project implements real-time car parking space detection using Python and computer vision libraries:
<ul>
  <li>OpenCV (cv2): Powerful library for real-time computer vision tasks.</li>
  <li>pickle: Used for saving and loading data in a binary format.</li>
  <li>cvzone: A library specifically designed for computer vision tasks.</li>
  <li>NumPy (np): Provides efficient numerical operations and array manipulation.</li>
</ul>

## Functionalites
<ul>
<li><b>Parking Space Selection (ParkingSpacePicker.py):</b> Allows interactive selection of the region of interest (ROI) in an image or video frame, encompassing the area where parking spaces are to be detected.
This ensures accuracy and adaptability to diverse parking lot layouts.
</li>
<li><b>Live Parking Space Counting (main.py):</b> This file utilizes computer vision to detect car parking spaces in real-time. It processes video frames (from webcam or video files), identifies potential space markers (lines, corners), refines the selected region, employs computer vision techniques to locate cars, and determines space occupancy based on car presence and size within bounding boxes. Finally, it counts and displays the number of available spaces.
</li>
