# How-to-Generate-Art-Demo
This is the improved code for "How to Generate Art - Intro to Deep Learning #8' by Siraj Raval on YouTube

##Overview

This is the code for [this](https://youtu.be/Oex0eWoU7AQ) video on Youtube by Siraj Raval as part of the Intro to Deep Learning Nanodegree with Udacity. We're going to re-purpose the pre-trained VGG16 convolutional network that won the ImageNet competition in 2014 for image classification to transfer the styles of a given image to another two. [This](https://arxiv.org/abs/1508.06576) is the original paper on the topic.


##Dependencies

run `pip install -r requirements.txt` to install the necessary dependencies


##Usage

If it doesn't exist, create a file called ~/.keras/keras.json and make sure it looks like the following:

   ````
   {
       "image_dim_ordering": "tf",
       "epsilon": 1e-07,
       "floatx": "float32",
       "backend": "tensorflow"
   }
   ````

Then you can run the code via typing `jupyter notebook` into terminal





