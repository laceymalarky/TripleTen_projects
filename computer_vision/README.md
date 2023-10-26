# Facial Age Detection using Computer Vision

## Project Overview
The supermarket chain Good Seed would like to explore whether Data Science can help them adhere to alcohol laws by making sure they do not sell alcohol to people underage. Their shops are equipped with cameras in the checkout area which are triggered when a person is buying alcohol. We will use computer vision methods to determine the age of a person from a photo by training a model using a set of photographs of people with their ages indicated.

## Machine Learning Skills/Technologies
Neural Networks, Data Generators, ResNet50 Architecture, Optimizers, Augmentations, GPU

## Project Conclusions
- Developed a [computer vision model](https://github.com/laceymalarky/TripleTen_projects/blob/main/computer_vision/facial_age_detection.ipynb) to determine the age of a person from a photo, achieving an 25% improvement in MAE.
- The model could predict ages with an average error of 6 years.
- Performed augmentations to optimize the images in the training set for modeling.

## Requirements
Python libraries: pandas, numpy, matplotlib, PIL, tensorflow

## Data Description:
- training and testing set of 7.6k photos
  - /datasets/faces/final_files/
- file with labels
  - /datasets/faces/labels.csv
    - `file_name` - name of the file in the corresponding folder with photos
    - `real_age` - actual age of the person in the photo
