Cam Ring Thickness Analysis Using Image Processing

📌 Introduction
This project focuses on measuring the thickness variation of a cam ring using digital image processing. The system automatically detects the ring edges and calculates thickness at multiple angles to analyze shape consistency.

🎯 Objective
To determine radial thickness variation of a cam ring image and generate a graphical representation of thickness distribution.

🧰 Tools & Libraries
Python
OpenCV
NumPy
Matplotlib
Pandas
Google Colab

🔍 Methodology

Step 1: Image Acquisition
The cam ring image is loaded from Google Drive or uploaded directly into Colab.

Step 2: Image Processing
Convert to grayscale
Apply Gaussian blur to reduce noise
Perform Canny edge detection

Step 3: Center Detection
Hough Circle Transform is used to detect the outer boundary and determine the center of the ring.

Step 4: Thickness Calculation
Scan radially from center (0°–360°)
Identify first edge (inner boundary)
Identify second edge (outer boundary)
Compute thickness in pixels

Step 5: Data Storage & Visualization
Store thickness values in CSV file
Plot thickness vs angle graph
Display processed image with radial lines

📈 Results
The program generates:
A processed image showing detected thickness lines
A graph showing thickness variation across angles
A CSV file containing measurement data

💡 Conclusion
This project demonstrates how computer vision techniques can be applied in mechanical inspection and quality control to measure dimensional variations accurately.
