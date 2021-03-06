# Face Recognition using Haar-Cascade Classifier, OpenCV, and Python
Simple Face Recognition algorithm using Python and OpenCV

## Requirement
- Python 3.5(https://www.python.org/downloads/release/python-350/)
- OpenCV 3.2.0 + contrib modules(pip install opencv-contrib-python)-Check this based on the os you are working(You need contrib module to run face recognition part)
- Numpy
- Mongodb(Start Mongodb server to run the application)

## Outline
This project consist of 3 parts, which are:
1. Creating datasets (face_datasets.py)(Registration Process)
2. Train the model (training.py)(Training Process)
3. Face Recognition (face_recognition.py)(Face Recognition Process)

## How to run ?
1. Please make sure that you have folders called 'dataset' and 'trainer' in the same directory
2. Run in the command line the face_datasets.py for taking your face image as datasets. Don't forget to set each person's face to unique ID (You need to edit the code everytime, or maybe just change the id variable to raw_input[OPTIONAL])
3. If you have more face to be include, change the ID and run the program again
4. Train your datasets by running training.py
5. Lastly, run face_recognition.py

## Reading materials
1. Object Detection using Haar-like features, link: http://www.cs.utexas.edu/~grauman/courses/spring2008/slides/Faces_demo.pdf
2. Face Detection using Haar Cascades, link: http://docs.opencv.org/trunk/d7/d8b/tutorial_py_face_detection.html
3. Haar-like Features, link: https://en.wikipedia.org/wiki/Haar-like_features
4. Object Detection using Haar-cascades Classifier, link: http://ds.cs.ut.ee/Members/artjom85/2014dss-course-media/Object%20detection%20using%20Haar-final.pdf
5. OpenCV Documentation, link: http://docs.opencv.org/3.0-beta/doc/py_tutorials/py_tutorials.html
