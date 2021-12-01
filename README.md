# Identifying Geologic Facies Through Seismic Dataset-to-Dataset Transfer Learning using Convolutional Neural Networks


Instructions for Code Organization 

This text file is designed to direct the viewer to the most important information in this code submission.

File type designated for jupyter notebooks or collab.

-	The “final_successful_turn_in.ipynb” is the main baseline training and transfer learning code used. For grading purposes, this is really the only file you should need to look at if you want a general idea of how the code works. All other folders contain jupyter notebook files with different hyperparameter combination results, data augmentation testing, and colorplot generating for our metric tests.
-	Any information contained outside the organized folders is considered to be important and the main code submission. This code file is the same format used as a baseline for changing hyperparameters. 

-	Folder called “Testing_Results” will be used to store hyperparameter combinations of the original “final_successful_turn_in.ipynb” file. 
-	Organized as “c32e_70b_u_net_train_transfer.ipynb” is one of many similar file types where 32 is the number of combined training and testing examples and 70 represents the last unfrozen layer. All hyperparameter tuning and results is at the bottom of the code file. 
-	“Deeplab_attempt_2.ipynb” contains our unsuccessful attempt at trying to integrate deep lab architecture with transfer learning
-	“Successful10examples.ipynb” is one of several files where were able to find successful hyperparameters with limited overfitting predictions. Again, see the bottom of the code file to see these results. 

-    Folder called “Data Augmentation” contains some of the work our group did in creating a backend method of data augmentation and making our dataset bigger. This was done during the last week of the project timeline and wasn’t fully integrated with transfer learning. However, we felt it was important to include in our file submission. 
  
-    Folder called “Pretrained Model Results” contains a code file that contains printed results and metrics of our successful pretrained model. The “final_succesfful_turn_in” file does not have the printed metrics from the callback so we wanted to include this just in case the grader would like to see this. 

- Folder called “Colorplot” contains code for how we generated one of our images for our metric visualization. 
