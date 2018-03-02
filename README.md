# OpenCV-Smartphone-Livestream-and-HAAR-Classifier
Allows you to run a HAAR classifier on a livestream from your Android Smartphone Camera

This repository allows you to use OpenCV3 on Python to display a live stream from your phone to your desktop. 

## Requirements

  * Python 3.3+ or Python 2.7
  * Windows or Linux (Not officially supported Linux)
  * OpenCV3
  * Urllib
  * Numpy
  
## How to Use

  1. Install IP Webcam app from the Google Play Store on an Android Smartphone and tap on "start server"
  
  2. Locate IPv4 server address on bottom of smartphone screen and replace in code shown below

  ```python
  url='http://192.168.1.68:8080/shot.jpg'
```
  3. Save and Run Python File!
  
  ## Note: 
  For those who would like to detect something besides faces, train or download your HAAR/LBP Cascade Model and replace file name in code shown below.
  
   ```python
  cascPath = "haarcascade_frontalface_default.xml"
```
  
  
