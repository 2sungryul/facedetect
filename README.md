# facedetect
This is the face detector using Yolov4 tiny model.

The Yolo weight and cfg files were taken from https://github.com/LorenRd/JetsonYolov4

# What to do on Jetson nano

Add in .bashrc as follows.

export DISPLAY=:0.0

xhost +

How to download, build, and run on Jetson nano

$ git clone https://github.com/2sungryul/facedetect.git

modify a destination ip address and port of gstreamer to those of your pc.

$ cd facedetect

$ make

$ ./facedetect

# What to do on Windows

Open the command prompt and download gst1.bat in a working directory

\> gst1.bat

![image](https://github.com/2sungryul/facedetect/assets/67367753/e70605ca-fde3-4547-945c-346b0ddbda6a)
