# CustomObjectDetection

## :memo:  Note
Create a new python environment and install all the required dependencies from requirements.txt

## :memo: Decription
In this project, we detect directions (namely left, right, up, down) from an image using the
ssd_mobilenet_v2_fpnlite_320x320 model pre-trained on the COCO dataset downloaded
from the Tensorflow Zoo repository.

Image collection process: We set up the folder paths, define image labels, collect images via
webcam using the OpenCV library, and then annotate the images using the labelimg tool.
Training process: Before training the model, we create label maps, TF records and update
the config file in compliance with our project, after training we load the model from the
checkpoints which were created during the training process.

Finally, we evaluate the model's performance by detecting directions on an unseen test
image and also on the real-time feed we receive from the webcam.



## :cloud: Algorithms and technologies used to build this model :-

1.  SSD MobileNet_V2_FPNLite_320x320
2.  Tensorflow Object Detection API
3.  OpenCV
