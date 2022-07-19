## Udacity AWS Machine Learning Engineer Nanodegree Capstone Project

# Brain Tumor Detection Using CNN

## Project Overview
Advancement in technology has resulted in the generation of a prodigious amount of data from everywhere. Due to the increasing amounts of electronic data in the healthcare, life sciences, and bioscience industry, medical doctors and physicians are facing problems in analyzing the data using traditional diagnosing systems. Nevertheless, machine learning and deep learning techniques have aided doctors and experts in detecting deadly diseases in their early stages.
The aim of this project is to build a Brain Tumor detection model using a Convolutional Neural Network using the Brain MRI Images Dataset.

## Dataset 
The dataset that will be used in this project is [Brain MRI Images for Brain Tumor Detection](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection). This dataset will be obtained from Kaggle. The dataset encompasses two folders named "yes" and "no." These folders collectively contain 253 brain MRI images. The images are grayscale and come in different sizes, i.e., they have distinct widths, heights, and the number of channels. The folder "yes" consists of 155 tumorous brain MRI images, and the folder "no" consists of 98 non-tumorous brain MRI images.

#### Dataset Public S3 URL Link: 
https://sagemaker-us-east-1-166360363896.s3.amazonaws.com/brain-mri-images-for-brain-tumor-detection.zip

## Project Proposal Review Link:
https://review.udacity.com/#!/reviews/3593589

## Libraries used in the project
1. **tensorflow** - used for training deep learning CNN VGG19 models
2. **cv2** - used for image processing
3. **imutils** - used for image processing
4. **shutil** - used for copying files

## Project Set Up and Installation
This project can be performed in any of the three softwares: **AWS Sagemaker Studio, Jupyter Lab/ Notebooks, or Google Colab**. Open the "capstone_project.ipynb" file and start by installing all the dependencies. For ease of use you may want to use a Kernel with GPU so that the training process is quick and time saving. 

The code requires creating 2 directories: "augmented_data," and "tumorous_and_nontumorous" which I have uploaded in AWS S3 bucket:

#### "augmented_data.zip" Public S3 URL Link: 
https://sagemaker-us-east-1-166360363896.s3.amazonaws.com/augmented_data.zip

#### "tumorous_and_nontumorous.zip" Public S3 URL Link: 
https://sagemaker-us-east-1-166360363896.s3.amazonaws.com/tumorous_and_nontumorous.zip

## Prediction Results
<img src="https://raw.githubusercontent.com/kanchitank/AWS-MLE-Nanodegree-Capstone/main/outputs/predictions.jpeg">
