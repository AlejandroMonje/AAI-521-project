# AAI-521-project
Group project by Alejandro Monje, Edgar Munoz, and Xavier Plasencia   

Classification and Segmentation of Cat & Dog Images

This project is a part of the AAI-521 course in the Applied Artificial Intelligence Program at the University of San Diego (USD).  -- Project Status: Completed

Prerequisites:

    First have either jupyter notebook installed and running (https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html) or use google colab (https://colab.research.google.com/) both are free resources that you can use to run our code on.
    kaggle accounnt: you can register for an account here (https://www.kaggle.com/account/login?phase=emailRegister)

Installation In order to run the code in this repository you will first have to get the the train.zip and test1.zip files from https://www.kaggle.com/competitions/dogs-vs-cats/data and put those files into your working directory. Open the AAI_521_Group3.ipynb file. Your path may be different than ours so you will have to update the path in the follwing sections: Once the path has been updated you should be able to run the rest of the cells in the in the file. If you would like to change the specific image to test the image segmentation portion on you can update the variable file which is in the second cell of the Classifying An Unseen Image Using Best Performing Model section.

Project Intro/Objective

The main purpose of this project is demonstrate our ability to create a machine learning model that takes in the images, classifies them, and lastly use the grabcut algorithm to perform image segmentation. The goal of this project is to have a model that can take in a dataset of images and accurately classify those images. In our case we used a dataset that consists of dog and cat images. We also want to to be able to perform image segmentation on these images. We can potentially use this

Describe the goals of the project and potential impacts. Mention the needs/applications of your project clearly. Limit to one/two short

Partner(s)/Contributor(s) Alejandro Monje: alejandromonje@sandiego.edu Edgar Munoz: edgarmunoz@sandiego.edu Xavier Plasencia: xplasencia@sandiego.edu

Methods Used:

    Exploratory Data Analysis
    Computer Vision
    Machine Learning
    Data Visualization
    Deep Learning (Convolutional Neural Networks)
    Pre-Trained VGG16 model
    GrabCut algorithm

Technologies

    Python
    jupyter notebook

We choose to use a kaggle dataset on cats and dogs (https://www.kaggle.com/competitions/dogs-vs-cats).
