# Simple-Facial-Expression-Detection
Human facial expression detection using OpenCV's dlib and pre-trained facial landmarks.

**Functionality**

• Uses OpenCV's dlib to detect face.

• Use specific indexes to get ROI(lips area) from the frame.

• Use a simple method to calculate slope between two points.

• Use the method stated in above point to detect the expression.

![image](https://user-images.githubusercontent.com/59373491/120938150-1edb2200-c72f-11eb-9d19-642319773827.png)

![image](https://user-images.githubusercontent.com/59373491/120938176-3dd9b400-c72f-11eb-82bb-080703738ab6.png)

**Packages used**

• OpenCV

• dlib

• imutils

• time

**Steps involved for detecting fingers**

1.	Detect face in the frame using dlib.
2.	Get the facial landmarks from the face using pre-trained model.
3.	Get the ROI (lips) from the frame.
4.	Calculate the slope between two points i.e., extreme lateral and horizontal points.
5.	Label the frame as happy or sad depending on the value of slope.


