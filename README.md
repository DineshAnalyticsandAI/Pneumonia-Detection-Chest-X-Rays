### Pneumonia Detection using Convolution Neural Network model on Chest XRays
### Tool Name : Pneumonia Reader Assistant (Detect Pneumonia using Convolution Neural Network on Chest X-Rays)
### Author Name:
Dinesh K.
### Name of your Device:
Pneumonia Reader Assistant

### Project Objective:
Develop a Radiologist Assistant - who can help in classifying a given chest x-ray for the presence or absence of pneumonia. Detect Pneumonia using Convolution Neural Network on Chest X-Rays
Intended Use Statement:
Assist radiologist in classifying a given chest x-ray for the presence or absence of pneumonia.

### Indications for Use:
Indicated for use in screening Pneumonia in males and females of ages 1-95 years having one or more combination of following diseases: atelectasis, heart enlargement, standardization, edema, effusion, emphysema, fibrosis, hernia, infiltration, mass, Creed, pleura thickening and pneumothorax.

### Project Overview
As part of this project/tool development, we will analyze data from the NIH Chest X-ray Dataset and train a CNN to classify a given chest x-ray for the presence or absence of pneumonia. This project will culminate in a model that can predict the presence of pneumonia with human radiologist-level accuracy that can be prepared for submission to the FDA for 510(k) clearance as software as a medical device. We will using 112,000 chest x-rays with disease labels acquired from 30,000 patients. GPU will be used for fast training of deep learning architecture. Upon completion of development, we would be able to:
1.	Recommend appropriate imaging modalities for common clinical applications of 2D medical imaging
2.	Perform exploratory data analysis (EDA) on medical imaging data to inform model training and explain model performance
3.	Establish the appropriate �ground truth� methodologies for training algorithms to label medical images
4.	Extract images from a DICOM dataset
5.	Train common CNN architectures to classify 2D medical images
6.	Translate outputs of medical imaging models for use by a clinician
7.	Plan necessary validations to prepare a medical imaging model for regulatory approval

### Project Steps/Tool Development steps
This project has the following steps. 1Exploratory Data Analysis 2.Building and Training Your Model 3.Clinical Workflow Integration 4. FDA Preparation

### Project Artificats
? EDA.ipynb ? Building and Training Your Model.ipynb ? Inference.ipynb ? Pneumonia_Classifier.json

### Overall Output metrics
1.	Maximum F1 score of this model at threshold of 0.58 is 0.4.
2.	This is slightly higher than average Radiologist F1 score which is at 0.38 as per ChexNet paper (https://arxiv.org/pdf/1711.05225.pdf).


