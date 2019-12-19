# Course_Project : Detecting cancerous cells in gigapixel images
This project is part of the COMS 4995 Topics in Computer Science- Applied Deep Learning Course.

Prof. Josh Gordon 

The data set used for the project is 21 slides of gigapixel pathology images.
A brief run through of the entire project along with the code has been done in the video link given below.

https://youtu.be/8KhpvgY9hUc

# Instructions to run the project: </br>
For smooth running of our notebooks you must first add this folder, named train_data, to your Google Drive:

https://drive.google.com/open?id=1Dw8OYwJWokRlqo9CJs_yql9K6Ev7lmu4

There are 3 notebooks in total. 

# image_generation.ipynb:
In this notebook, we are generating a thousand images from each of the 21 slides we are given. We save the image and its corresponding mask to a Google Drive folder. We also include code from some of our other data testing and cleansing tasks.This is basically the image preprocessing part of the project. 

# heatmap_model.ipynb
In this notebook, we are training our heatmap neural network model. We will first preprocess the input image using inception_v3 into a vector representation with 2048 attributes. Using this vector, we attempt to define a model that decodes the vector into the heatmap corresponding to this particular image

# prediction.ipynb
This code is designed to allow you to easily generate a heatmap for a cancer slides.This is the only code you are supposed to run to see the detection of cancerous images. 

Authors of this projects are :

Name: Patrick Stanton                
UNI : pws2111

Name: Prajwal Prakash </br>
UNI: pp2719
