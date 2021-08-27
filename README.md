# facemaskdetection
The objective of this project is to detect whether a person is wearing a mask or not. This project is developed using You Only Look Once (YOLO) model. This algorithm is popular because of its speed and accuracy in detecting objects. Most of the industries prefer YOLO for the same reasons. 
Keeping this in mind, I have used this model to get the better precision. 
In this project, I have used the dataset which includes with mask and without mask images. To train the yolo model, the most important thing is to annotate images using labelImg tool for bounding box co-ordinates and respective class labels. This algorithm applies single neural network to the full image and then divides the image into regions and predicts those bounding boxes and probabilities for each region.
In training the model, we use pretrained weight file and configurations file from https://github.com/AlexeyAB/darknet.

The labelImg tool used for annotating images can be downloaded from here https://github.com/tzutalin/labelImg.
