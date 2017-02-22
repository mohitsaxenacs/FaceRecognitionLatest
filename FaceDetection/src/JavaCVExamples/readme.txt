This directory contains 1 Java example:
  * FaceDetection.java

There are 2 JPG files:
  * group.jpg, lena.jpg

There is 1 XML file, containing a Haar classifier for faces:
  * haarcascade_frontalface_alt.xml
         -- this was copied from the OpenCV directory: 
            <OpenCV>\data\haarcascades\

There are 2 batch files:
  * compile.bat
  * run.bat
     - make sure they refer to the correct locations for your
       downloads of JavaCV and OpenCV


----------------------------
Before Compilation/Execution:

You need to download and install:

  * OpenCV:  I downloaded v2.4.9 for Windows with pre-compiled binaries:
             from http://opencv.org/downloads.html
             and installed it in desired location

  * JavaCV:  http://code.google.com/p/javacv/
             I downloaded javacv-0.9-bin.zip
             and installed it in desired location

----------------------------
Compilation:

> compile *.java
    // you must have JavaCV and OpenCV installed

----------------------------
Execution:
    // you must have JavaCV and OpenCV installed for this example to work


> run FaceDetection <image file>
e.g.
> run FaceDetection group.jpg
     -- the code will load the classifier from haarcascade_frontalface_alt.xml
     -- the image with all faces highlighted is stored in markedFaces.jpg

----------------------------
