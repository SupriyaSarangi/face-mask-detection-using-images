# face-mask-detection-using-images
the project is built using Tensorlow, Keras and OpenCV

With the novel coronavirus or also called as the COVID-19 pandemic that still continues to thrive in our country day by day, safety plays an important issue.
There have been guidelines issuing the importance of wearing face-masks while stepping out of the house for any necessity. For the purpose, to check whether or not
the people are abiding by this rule, it has become number one priority to make sure they are wearing masks at any public place. This is where face-mask-detection comes into picture.

The project is built using Deep learning technique called as Convolutional neural networks (CNN). This CNN model is made using Tensorflow libraries followed by Keras for computing and OpenCV for visualization. We are classifying the data in two classes:

-with_mask - 690 images

-without_mask - 686 images

The dataset is available in the repository above.

##Installation

-- clone the repository

$ git clone

-- install the libraries by typing the command as shown below

$ pip3 install -r libraries.txt


##Working

-- open command prompt in windows and change the path to where you have saved the project

for eg: C:\face_mask>

--open jupyter-notebook in the same directory

C:\face-mask>jupter-notebook

--run the mask_detetction_training.ipynb file

--the model gets saved in .h5 format

--now open python IDLE-3.7.1 shell and open the detect_images.py file

--click run module to observe the result


The training accuracy of the model is about 97%
