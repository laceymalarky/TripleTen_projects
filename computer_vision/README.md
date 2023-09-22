# Facial Age Detection using Computer Vision

## Project Overview
The supermarket chain Good Seed would like to explore whether Data Science can help them adhere to alcohol laws by making sure they do not sell alcohol to people underage. Their shops are equipped with cameras in the checkout area which are triggered when a person is buying alcohol We will use computer vision methods to determine the age of a person from a photo by training a model using a set of photographs of people with their ages indicated.

## Technologies
Neural Networks, Data Generators, ResNet50 Architecture, Optimizers, Augmentations, GPU

## Project Conclusions
- The final model has a MAE on the test set of 6.09, so there is a +/- 6 year difference between the actual and predicted values on average.
- This model might not be the best solution to help the customer ensure they do not sell alcohol to people underage since the error for this model is relatively large.
- Possible model improvements:
  - The model could be improved by increasing the amount of training data. We should also make sure that the data is diverse and representative so it captures complexities of real-world data.
  - Try other computer vision models and continue to tune the hyperparameters of this model and compare the results.
  - Additional augmentations
  - Introduce additional layers with normalization methods
  - Try other optimizers (e.g., AdamW)

## Requirements
Python libraries: pandas, numpy, matplotlib, PIL, tensorflow

## Data Description:
- training and testing set of 7.6k photos
  - /datasets/faces/final_files/
- file with labels
  - /datasets/faces/labels.csv
    - `file_name` - name of the file in the corresponding folder with photos
    - `real_age` - actual age of the person in the photo


