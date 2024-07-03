Custom Object Detection using YOLOv5
This project focuses on detecting custom objects, specifically traffic signs, using the YOLOv5 model. The aim is to classify these signs into different categories and train a model that can accurately detect and classify them.

Objectives
Fine-tune the YOLOv5 model on a custom dataset.
Detect traffic signs and categorize them into four classes:
Speed limit signs
Warning signs
Indication/announcement signs
Other classifications
Dataset Preparation
To train our model, we need a well-organized dataset with images and corresponding labels. The labels must specify the coordinates of the traffic signs in the images and their respective classes. The coordinates are normalized to values less than 1. The dataset should be structured as follows:

Images: Stored in a folder named images
Subfolders: train and val for training and validation sets respectively.
Labels: Stored in a folder named labels
Subfolders: train and val matching the image dataset structure.
This organization facilitates efficient training and testing of the model.
