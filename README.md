# Helmet-Detection
Helmet Detection using YOLOV3
Its a simple YOLO model to detect and count the number of people wearing helmet in a image. this model can be used to detect the intrusion or to find the people ridding bike without helmet.

Here you can read my post in detail  https://medium.com/@vijaysingh_60587/train-your-own-custom-model-for-helmet-detection-object-detection-using-yolo-f53a48066d7a

Getting Started
#### This code is very simple and with the help of little manipulation, you can count the number of detection for a particular detection.
#### or extract the co-ordinates of bounding boxes. download the models, create necessary files and give full path to the models and folder names and run the python script.

#### training:  
  if you want to train your own model, follow the [darknet](https://github.com/AlexeyAB/darknet).
Prerequisites  
install python3.  
install pip3.  
install opencv.( sudo pip3 install opencv-python ).  

install other liberaries  if missing.  


After setting up the paths.  
change the path of classfile in line 19,  
change the path of configuration file in line 25,  
change the path of weights in line 26  
change the output folder name in line 133 where you want to keep your output files.  
change the name of folder in line 150 for input images.  
, it's ready to run.  
open terminal and python3 Helmet_detection_YOLOV3.py  

#### link to files.  
[model](https://drive.google.com/file/d/1_xBdP1GRK4i7yzJP8_a5GWaejZZKjdyI/view?usp=sharing)
[model1](https://drive.google.com/file/d/13OOejC0MKb2aY2hE8zVXGx50aSQuK4Lg/view?usp=sharing)
[cfg](https://drive.google.com/file/d/1GM1eS5PNJTNFPytQsmnv7rgw2nle1bnW/view?usp=sharing)  
[obj.names](https://drive.google.com/file/d/1mvJHjmRCWgi6wxPFaw7ZM5i7aCAWk3J4/view?usp=sharing)  
If everything went well. you will get results like this  e 19,
change the path of configuration file in line 25,
change the path of weights in line 26
change the output folder name in line 133 where you want to keep your output files.
change the name of folder in line 150 for input images.
, it's ready to run.
open terminal and python3 Helmet_detection_YOLOV3.py
