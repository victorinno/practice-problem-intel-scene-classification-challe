# practice-problem-intel-scene-classification-challe

## About Practice Problem Intel Scene Classification Challenge
There has been a tremendous increase in the applications of computer vision. The applications of CV range from smart cameras and video surveillance to robotics, transportation and more.

Intel remains at the forefront to enable developers and data scientists build useful CV applications optimised for Intel processor architecture.

We encourage the participants to use the new OpenVINO™ toolkit by Intel. Short for Open Visual Inference & Neural Network Optimisation, the OpenVINO™ toolkit (formerly Intel® CV SDK) contains optimised OpenCV and OpenVX libraries, deep learning code samples, and pre-trained models to enhance computer vision development.  It’s validated on 100+ open source and custom models, and is available absolutely free. You can get started with the toolkit from the resources provided at this link

## Problem Statement
How do we, humans, recognize a forest as a forest or a mountain as a mountain? We are very good at categorizing scenes based on the semantic representation and object affinity, but we know very little about the processing and encoding of natural scene categories in the human brain. In this practice problem, you are provided with a dataset of ~25k images from a wide range of natural scenes from all around the world. Your task is to identify which natural scene can the image be categorized into.

## DATASET DESCRIPTION
There are 17034 images in train and 7301 images in test data.
The categories of natural scenes and their corresponding labels in the dataset are as follows -

{     'buildings' -> 0,     'forest' -> 1,     'glacier' -> 2,     'mountain' -> 3,     'sea' -> 4,     'street' -> 5 }

There are three files provided to you, viz train.zip, test.csv and sample_submission.csv which have the following structure.
## Variable	Definition
image_name	Name of the image in the dataset (ID column)
label	Category of natural scene (target column)
train.zip contains the images corresponding to both train and test set along with the true labels for train set images in train.csv
## EVALUATION METRIC
The Evaluation metric for this competition is accuracy.

## PUBLIC AND PRIVATE SPLIT
Public leaderboard is based on 30% of the test data, while private leaderboard will be evaluated on remaining 70% of the test dataset.
