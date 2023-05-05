
## Facial Detection and Extraction using OpenCV and Haar Cascade Algorithm (WORK IN PROGRESS)

This project demonstrates how to detect faces using OpenCV and Haar Cascade Algorithm, and extract them from an image. The project is designed to work with a CSI camera, but can also work with other cameras.

### Requirements

-   Python 3.x
-   OpenCV
-   face_recognition
-   Haar Cascade XML file
-   CSI Camera or other camera

### Installation

1.  Install OpenCV by running the following command in the terminal:
    
    `pip install opencv-python` 
    
2.  Download the Haar Cascade XML file from [OpenCV GitHub repository](https://github.com/opencv/opencv/tree/master/data/haarcascades).
    
3.  Clone or download the project repository to your local machine.

4. Install the face_recognition library by running the following command in the terminal:

pip install face_recognition

Note: face_recognition requires NumPy, dlib, and Click to be installed as well. If you have any issues with installation, refer to the official installation guide.

This installation guide assumes that you already have Python and pip installed on your machine. If not, you will need to install them first before proceeding with the installation of OpenCV and face_recognition.    

### Usage

1.  Connect the CSI camera or other camera to your device.
    
2.  Run the `main.py` file from the project directory in the terminal:
    
    `python main.py` 

    

### Credits

This project was inspired by the following sources:

-   [OpenCV documentation](https://opencv.org/)
-   [천동이] (https://blog.naver.com/chandong83/221695462391)