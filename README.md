# A very Simple Gui app for Face Detection 
## Project Description:
The Face Recognition System is a Python-based project that utilizes OpenCV, a popular computer vision library, to create a robust and accurate face recognition system. The system is capable of detecting and recognizing faces in real-time using a webcam or by processing images and videos. It provides functionalities such as adding new users, capturing face images for training, training a custom classifier, and performing face recognition on live video streams.

## Libraries Used:

- OpenCV: OpenCV (Open Source Computer Vision Library) is a powerful open-source library for computer vision and image processing tasks. It provides various functions and algorithms for face detection, recognition, and image manipulation.

- Tkinter: Tkinter is a standard Python interface for creating graphical user interfaces (GUI). It is used in this project to develop an interactive and user-friendly interface for the face recognition system.

- PIL (Python Imaging Library): PIL is a library for handling images in Python. It is used in this project to load, process, and save images.

## Key Features:

- Face Detection: The system uses the Haar cascade classifier provided by OpenCV to detect faces in images and video streams.
- User Management: Users can be added to the system by providing their names. The system maintains a list of registered users.
- Dataset Creation: The system allows capturing face images of users to create a custom dataset for training the face recognition model.
- Model Training: The captured face images are used to train a custom classifier based on the Local Binary Patterns Histograms (LBPH) algorithm provided by OpenCV.
- Real-time Face Recognition: The trained model is used to perform real-time face recognition on live video streams, identifying registered users.
- Graphical User Interface: The system provides an intuitive GUI developed using Tkinter for easy navigation and interaction with different functionalities.
## Accuracy and Performance:
- The accuracy of the face recognition system depends on various factors such as the quality of input images, lighting conditions, and the size of the dataset used for training.
- To achieve better accuracy, it is recommended to capture a sufficient number of face images per user during the dataset creation phase (e.g., at least 300 images).
  
# Installation

1 : Install the requirements.

```sh
$ pip install -r  requirements.txt
```

2 : Run The App 

```sh
$ python app-gui.py
```

# APP GUI

### Home Page
![homepage](https://i.ibb.co/c62qvR2/home-page.png)

### Add a User <br>
Add the user you want to train a classifier for <br>
![page1](https://i.ibb.co/t8gdq6s/adduser.png)<br>


### Capture Data and Train Classifier<br>
Capture Data From the face then train the classifier<br>
![page2](https://i.ibb.co/D8JgYhN/capandtraindata.png)<br>

### Users List<br>
List of all the users<br>
![page3](https://i.ibb.co/1KwfVVV/dropdown.png)<br>

<br><br>

Made By ❤ : [WajahatAliBasharat](mailto:wajahatalibasharat073@gmail.com)<br>
**Free Software**
**Soon new feature will be added**
- emotion recognition
- gender recognition



