# Blind-Assistance-Using-ML--Object-Detection-and-Voice-Feedback
With the recent rapid development of information technology (IT), a lot of research has been carried out to solve inconveniences in everyday life, and as a result, various conveniences for people have been provided. Nevertheless, there are still many inconveniences for the visually impaired. The greatest inconveniences that a blind person feels in everyday life include finding information about objects and indoor mobility problems. They have difficulty recognizing simple objects, and it is not easy to distinguish objects that have similar forms. Previous studies included object analysis using ultrasonic sensors. However, with these methods, it is difficult to know exactly where an object is located, especially in the presence of obstacles. In this project, we analyze accurate object information and obtain a location using a deep learning object recognition technique. In addition, voice recognition and voice guidance technologies are synthesized so the visually impaired can know the location of the objects they want to find by speaking to the system.

Overview

![overview](https://user-images.githubusercontent.com/71813503/193608555-e883b4b7-f7f5-4cdb-867d-af6125804ea5.png)

Steps to execute :

Download the code in a zip file from github repository

Extracted the downloaded zip file

Download yolov3.weights file from the below link

This file was too large for github repository

Hence yolov3.weights can be downloaded from the below link :

https://drive.google.com/file/d/1OyO0CACnyFzz5qAwhEX9idpbrqAJx_Wo/view?usp=sharing

Cut paste the downloaded file inside yolo-coco folder

Open cmd prompt inside the source code folder and execute the file with the following command

python script.py --image images/dog.jpg --yolo yolo-coco
