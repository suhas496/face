This repository contains a Python-based face detection project that utilizes a pre-trained model from Google Teachable Machine. It provides an easy-to-implement solution for detecting faces in both images and live video streams using machine learning techniques.

Features
Detects faces in static images and real-time video streams.
Uses a pre-trained model from Google Teachable Machine.
Beginner-friendly and highly customizable.
Prerequisites
Python 3.7 or higher
OpenCV library
NumPy library
A pre-trained face detection model from Google Teachable Machine
Installation Instructions
Step 1: Open Google Chrome and navigate to the Google Teachable Machine website. Click on Get Started.

Step 2: Under the New Project section, select Image Model.

Step 3: Choose the Standard Image Model option.

Step 4: Define the necessary classes and upload images using your webcam or Google Drive. Train the model and observe the comparison percentages for the selected classes.

Step 5: After training, click Export the Model.

Step 6: In the TensorFlow tab, select Download the Model. A .zip file will be downloaded.

Step 7: To run the project locally, open your Python code editor (e.g., PyCharm) and paste the provided code.

Step 8: Extract the .zip file, copy the .h5 model file and the .txt class labels file, and place them in your project directory.

Step 9: Open the terminal and install the required libraries for the project. Ensure you're using the correct Python and TensorFlow versions to avoid syntax errors.

Step 10: Run the code, and the FaceFinder+ model should work for face detection.
