# Facial keypoints detection.


# Description:

## In this project we are detecting facial keypoints of  a given person.According to the face features the model will detect the keypoints so it can be 4 or 15 keypoints.


# Project Structure

1. I have taken dataset from kaggle.
2. Preprocessed the dataset and made 3 different files
    - First file has the complete data.
    - Second file has the datapoints which having 4 keypoints.
    - Third file has the datapoints which having 15 keypoints.
3. Model Training
    - I have developed single model using Transfer Learning for detecting both types but we can train single model for each i.e one model for 4 keypoints and one model for 15 keypoints.
    - EfficientNet Model was used for Training.
4. The accuracy of this model can be improved.I have trained this model only for few epochs.If the model would have been trained for some more epochs the accuracy would have been increased.Also I have already mentioned above 2 models approach we can leverage that as well. 

# Libraries
1. Pytorch
2. Albumentations
3. Cv2

   
