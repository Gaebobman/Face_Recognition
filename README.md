
## Facial Detection and Extraction using OpenCV and Haar Cascade Algorithm (WORK IN PROGRESS)

This project demonstrates how to detect faces using OpenCV and Haar Cascade Algorithm, and extract them from an image. The project is designed to work with a CSI camera, but can also work with other cameras.

### Requirements

-   Python 3.x
-   OpenCV
-   Haar Cascade XML file
-   CSI Camera or other camera

### Installation

1.  Install OpenCV by running the following command in the terminal:
    
    `pip install opencv-python` 
    
2.  Download the Haar Cascade XML file from [OpenCV GitHub repository](https://github.com/opencv/opencv/tree/master/data/haarcascades).
    
3.  Clone or download the project repository to your local machine.
    

### Usage

1.  Connect the CSI camera or other camera to your device.
    
2.  Run the `main.py` file from the project directory in the terminal:
    
    `python main.py` 
    
3.  Choose the `1: Register` option to register a new user.
    
4.  Enter the user's name when prompted.
    
5.  Capture the user's image using the camera by pressing the 'c' key.
    
6.  If the capture is successful, the detected faces will be highlighted with a grid and numbered. Choose the grid number of the desired face to extract.
    
7.  Once the grid number is chosen, the face will be extracted, converted to grayscale, and saved to the `data/sub_data` directory with the user's name as the filename.
    

### Credits

This project was inspired by the following sources:

-   [OpenCV documentation](https://opencv.org/)
-   [076923's blog](https://076923.github.io/posts/Python-opencv-2/)
-   [Scribbling Anything's blog](https://scribblinganything.tistory.com/472)
-   [ai0's blog](https://ai0.kr/m/41)