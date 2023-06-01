# CS776A-Deep-Learning-for-Computer-Vision
Deep Learning for Computer Vision (CS776A): Assignment I

Submitted By: Allan Robey (22111007)<br>
email-allanrobey22@iitk.ac.in

##Libraries Required:
pytorch

torchvison

opencv

numpy

matplotlib

pickle

sklearn

random 

math

PIL 


######################################################################################################################################

Our main file is allan22111007.ipnyb file . To run the whole file we need to have data_batch_1,data_batch_2,data_batch_3,data_batch_4,data_batch_5,test_batch from the given data set in the our directory .This should take about 2-3 hrs to execute.

Running the whole file is time consuming so we have made pickle files for each question so that we can run each question individually.The details of the pickle files are as follows:

1.'train_data.pkl'- Contains combined data images of all the 5 data batch files(data_batch_1,data_batch_2,data_batch_3,data_batch_4,data_batch_5).
2.'test_data.pkl'- Contains test data images
3.'train_data_labels.pkl'-Contains combined data lables of all 5 data batch files(data_batch_1,data_batch_2,data_batch_3,data_batch_4,data_batch_5).
4.'test_data_labels.pkl'- Contains test data labels
5.'train_aug_data.pkl'-Contains augmented train data images 
6.'test_aug_data.pkl'- Contains augmented test data images
7.'train_aug_lables.pkl'- Contains augmented train data labels
8.'test_aug_lables.pkl'- Contains augmented test data labels
11.'train_feature_vector.pkl'- Contains 1d feature vector of images from train data.This file contains total of 100000 feature vector of which the first 50000 are of original train data and the rest are augmented images feature vector
12.'test_feature_vector.pkl'-Contains 1d feature vector of images from train data.This file contains total of 20000 feature vector of which the first 10000 are of original test data and the rest are augmented test images feature vector



To Run a specific Question you just need to run the cell of that of particular question.

######################################################################################################################################

Directory Substructure:
All the files need to be kept at in a single folder.



In the submission we have just given our main file. To download the all pickle files, data files,together with main file pls refer this link https://drive.google.com/drive/folders/1UvXnbkRCJg1NfIZuZd3x38W6lCXX0OG6?usp=sharing  & download the folder .

After downloading the above folder you can execute any Question you want to run .

