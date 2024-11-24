
# PYTHON PROJECTS

This repository contains Python scripts that utilize MediaPipe and OpenCV for different real-time computer vision applications.

## Requirements

- Python 3.x
- OpenCV
- MediaPipe

You can install the required libraries using pip. To do so, create a virtual environment and install the dependencies from the requirements.txt file.

## Cloning the Repository

To clone this repository to your local machine, run the following command in your terminal:

    git clone https://github.com/AaronKurian/Py-projects.git

Navigate to the repository folder:

    cd Py-projects

Install the required dependencies:

    pip install -r requirements.txt


Alternatively, you can install the dependencies individually:

    pip install opencv-python mediapipe


## Running the Program

For Static Images:
        Modify the IMAGE_FILES list in the script with paths to your image files.
       
For Webcam Input:
        Simply run the script and allow it to access your webcam for real-time detection:
           ```
            python3 face_detection.py
           ```
           ```
            python3 face_mesh.py
           ```
           ```
            python3 hand_detection.py
           ```
            
## Scripts Overview

### 1. `face_detection.py`

This script detects faces in static images and webcam input using MediaPipe's Face Detection solution. It draws bounding boxes around detected faces and prints the coordinates of the nose tip.

### 2. `face_mesh.py`

This script uses MediaPipe's Face Mesh to detect facial landmarks in both static images and webcam input. It draws intricate face mesh contours and connections for detailed facial landmark visualization.

### 3. `hand_detection.py`

This script detects hand landmarks using MediaPipe's Hands solution in both static images and webcam input. It draws hand landmarks and connections, and outputs the coordinates of key landmarks like the index finger tip.


## 💡 Contributions

Feel free to contribute by submitting new solutions, optimized code, or explanations for any program in this repository. Simply fork the repository and open a pull request!


## License

This project is licensed under the [MIT License](LICENSE.md)

Made With ❤️ by Aaron Kurian Abraham

