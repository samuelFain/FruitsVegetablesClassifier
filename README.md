# Computer Vision Project - Fruits & Vegetables Classifier

![output](https://user-images.githubusercontent.com/65926551/152634780-a354f493-53cf-4d3b-97a5-e71451cabd89.png)
##
Our goal for this project was to create a PyTorch based computer vision model, dedicated to identifying & classifying a large variety of fruits & vegetables.

To achieve this goal, our project will include all the necessary steps including creating and training a CNN-based deep learning model, working with a large dataset of labeled images, 
handling input images for classification and testing.

** the notebooks in this project are fully documented **

## Example of the model prediction based on an mp4 video input conataining images from the testing dataset:
![video_feature](https://user-images.githubusercontent.com/65926551/152635424-df034fe7-d4b8-49d9-8908-9014d725e37c.gif)

## Libraries
- os
- torch
- torchvision 
- tarfile
- matplotlib  
- cv2 (openCV)

## Tools
- Dataset: “Fruits 360” <br>
https://www.kaggle.com/moltean/fruits
- Deep Learning Framework: Pytorch
- Anaconda
- Python 3.9.7
- Jupyter notebooks/Visual Studio Code

## Further Improvements
- Condition & Quality - It’s possible to improve our model by creating a dataset containing labeled images of fruits/vegetables with different conditions, defects or damage, and teaching our model to identify and grade the quality of fruits/vegetables in addition to classification abilities. 
- Video Classification - although we successfully managed to implement video classification feature in out project, it is far from perfect.
There are a lot of improvements to be made, such as live boundering boxes, predicting multiple images in a frame, and faster overall performance.
- Diversify the dataset - as mentioned, our experiments led to the conclusion that the dataset is not diverse enough, hence the need to diversify the data set for a more flexible and capable model predictions. 


## Bibliography
“Building a Deep Learning model with Pytorch to classify fruits and vegetables”<br />
https://medium.com/swlh/building-a-deep-learning-model-with-pytorch-to-classify-fruits-and-vegetables-30e1a8ffbe8c<br />


“Build an Image Classification Model using Convolutional Neural Networks in PyTorch”<br />
https://www.analyticsvidhya.com/blog/2019/10/building-image-classification-models-cnn-pytorch/<br />

Fruits 360 dataset by “kaggle” <br />
https://www.kaggle.com/moltean/fruits <br />


“Implementing Real-time Object Detection System using PyTorch and OpenCV” <br />
https://towardsdatascience.com/implementing-real-time-object-detection-system-using-pytorch-and-opencv-70bac41148f7
https://towardsdatascience.com/object-detection-and-tracking-in-pytorch-b3cf1a696a98<br />
