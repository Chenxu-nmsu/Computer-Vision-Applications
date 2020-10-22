# Computer Vision Applications

### 01 Document Scanner
- Demo
<table>
 <tr>
    <td><b style="font-size:16px">Edge detection</b></td>
    <td><b style="font-size:16px">Image Alignment</b></td>
 </tr>
 <tr>
    <td><image src="images/01_document_scanner_1.png" width =300px /></td>
    <td><image src="images/01_document_scanner_2.png" width =300px /></td>
 </tr>
 </table>

- Introduction
Build a document scanner using Edge Detection, Finding Contours and Perspective Transformation.

- Running Command
```sh
python scan.py --image images/page.jpg
```

### 02 Optical Mark Recognition
- Demo
<table>
 <tr>
    <td><b style="font-size:16px">Submitted Assignment</b></td>
    <td><b style="font-size:16px">Auto Graded Assignment</b></td>
 </tr>
 <tr>
    <td><image src="images/02_optical_mark_1.png" width =300px /></td>
    <td><image src="images/02_optical_mark_2.png" width =300px /></td>
 </tr>
 </table>

- Introduction
Implement a bubble sheet scanner and grader using OMR (Optical Mark Recognition), Python, and OpenCV

- Running Command
```sh
python test_grader.py --image images/test_01.png
```

### 03 Size of Objects
- Demo
<table>
 <tr>
    <td><b style="font-size:16px">Auto Size Measurement</b></td>
 </tr>
 <tr>
    <td><image src="images/03_size_of_the_object.gif" width =300px /></td>
 </tr>
 </table>

- Introduction
Measure the size of objects in an image using OpenCV.

- Running Command
```sh
python test_grader.py --image images/test_01.png
```

### 04 Real-time Object Detection
- Demo
<table>
 <tr>
    <td><b style="font-size:16px">Real-time Object Detection</b></td>
 </tr>
 <tr>
    <td><image src="images/05_real_time_object_detection.gif" width =300px /></td>
 </tr>
 </table>

- Introduction
A real-time object detection with deep learning and OpenCV.

- Running Command
```sh
python real_time_object_detection.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel
```

### 05 Face Detection
- Demo
<table>
 <tr>
    <td><b style="font-size:16px">One Face</b></td>
    <td><b style="font-size:16px">Two Faces</b></td>
 </tr>
 <tr>
    <td><image src="images/06_face_detection_1.png" width =300px /></td>
    <td><image src="images/06_face_detection_2.png" width =300px /></td>
 </tr>
 </table>

- Introduction
A face detection with OpenCV and deep learning.

- Running Command
```sh
python test_grader.py --image images/test_01.png
```

### 06 Face Landmarks
- Demo
<table>
 <tr>
    <td><image src="images/07_face_landmark_01.png" width =300px /></td>
    <td><image src="images/07_face_landmark_02.png" width =300px /></td>
 </tr>
 <tr>
    <td><image src="images/07_face_landmark_03.png" width =300px /></td>
    <td><image src="images/07_face_landmark_04.png" width =300px /></td>
 </tr>
 </table>

- Introduction
Detect facial landmarks with dlib, OpenCV, and Python.

- Running Command
- one face
```sh
python detect_faces.py --image images/one_face_1.jpg --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel
```
- two faces
```sh
python detect_faces.py --image images/two_face_1.jpg --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel
```

## 07 Blink Detection
- Demo
<table>
 <tr>
    <td><b style="font-size:16px">Counting Blinks</b></td>
 </tr>
 <tr>
    <td><image src="images/08_blick_detection.gif" width =300px /></td>
 </tr>
 </table>

- Introduction
Build an eye blink detection with OpenCV, Python, and dlib.

- Running Command
```sh
python detect_blinks.py --shape-predictor shape_predictor_68_face_landmarks.dat
```

## 08 Drowsiness Detection 
- Demo
<table>
 <tr>
    <td><b style="font-size:16px">Drowsiness Detection</b></td>
 </tr>
 <tr>
    <td><image src="images/09_drowsiness_detection.gif" width =300px /></td>
 </tr>
 </table>

- Introduction
Build a drowsiness detection using OpenCV and face landmark detection.

- Running Command
```sh
python detect_drowsiness.py --shape-predictor shape_predictor_68_face_landmarks.dat
```
## Requirements
- numpy
- argparse
- cv2
- imutils
- scipy
- dlib

## References
- <https://www.pyimagesearch.com/>
