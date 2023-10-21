# Face_recognition
Face Detection with Python using CV2
This repository contains a Python script for real-time face detection and recognition using OpenCV and face_recognition libraries. The script captures video from the default camera, detects faces in the video frames, and recognizes known faces based on pre-loaded images of Barack Obama and Joe Biden.

Prerequisites
To run this script, you need to have Python installed on your machine along with the following libraries:

OpenCV: For capturing video and rendering the detection results.
face_recognition: For face detection and recognition.
numpy: For numerical operations.
You can install these libraries using pip:

sh
Copy code
pip install opencv-python face_recognition numpy
How to Run
Clone this repository to your local machine.
Place the images of the people you want to recognize in the project directory and note down their file names.
Update the main.py script to load your images and set the correct file paths.
Open a terminal in the project directory.
Run the script using Python:
sh
Copy code
python main.py
How it Works
Capture Video: The script captures video from the default camera.
Load and Encode Faces: It pre-loads images of known individuals and encodes their faces. In this example, images of Barack Obama and Joe Biden are used.
Detect and Recognize Faces: For each frame in the video, the script detects faces and tries to recognize them based on the pre-loaded encodings.
Annotate Video: If a face is recognized, the script draws a box around the face and labels it with the individual's name.
Display Results: The annotated video is displayed in real-time.
Exit: Press 'q' to exit the program.
Dependencies
OpenCV: Used for capturing video and rendering the detection results.
face_recognition: Used for face detection and recognition.
numpy: Used for numerical operations.
Acknowledgements
This project uses the face_recognition library, which is built on top of dlib, a modern C++ toolkit containing machine learning algorithms and tools for creating complex software in C++ to solve real-world problems.

Feel free to modify and use this project as per your needs. If you have any questions or need further assistance, please open an issue in this repository.
