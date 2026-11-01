# Face Detection using OpenCV Haar Cascade

## 1. Introduction

Face Detection is a Computer Vision technique used to identify and locate human faces in images and video streams.

This project demonstrates face detection using OpenCV and the Haar Cascade Classifier.

## 2. Technologies Used

- Python
- OpenCV
- NumPy
- Haar Cascade Classifier
- Google Colab

## 3. Haar Cascade Classifier

Haar Cascade is a pre-trained machine learning-based object detection method available in OpenCV.

In this project, the `haarcascade_frontalface_alt.xml` model is used to detect frontal human faces.

## 4. Image-Based Face Detection

### Objective

To identify human faces in an input image and highlight them using rectangular bounding boxes.

### Working Process

1. Load the pre-trained Haar Cascade face detection model.
2. Read the input image.
3. Convert the image from BGR to grayscale.
4. Apply the Haar Cascade classifier to detect faces.
5. Retrieve the coordinates of detected faces.
6. Draw rectangular bounding boxes around the detected faces.
7. Display the final output image.

### Output

The system detects faces in the input image and highlights each detected face with a rectangular bounding box.

## 5. Live Webcam Face Detection

### Objective

To detect human faces continuously from a live webcam video stream.

### Working Process

1. Initialize the webcam.
2. Capture video frames continuously.
3. Convert each captured frame into grayscale.
4. Apply the Haar Cascade classifier to detect faces.
5. Extract the coordinates of detected faces.
6. Draw rectangular bounding boxes around detected faces.
7. Display the processed video frames continuously.
8. Stop the webcam when the user exits the application.

### Output

The system detects human faces from the live webcam stream and displays rectangular bounding boxes around detected faces.

**Note:** Google Colab requires browser-based webcam access. For direct OpenCV webcam access using `VideoCapture(0)`, a local Python environment such as Jupyter Notebook or VS Code is recommended.

## 6. Key Concepts Learned

- Computer Vision
- Image Processing
- Grayscale Conversion
- Haar Cascade Classification
- Face Detection
- Bounding Box Visualization
- Webcam Video Processing
- Real-Time Frame Processing

## 7. Conclusion

This project demonstrates two approaches to face detection using OpenCV Haar Cascade Classifier: image-based face detection and live webcam face detection.

It provides practical experience with fundamental Computer Vision techniques and image processing operations.
