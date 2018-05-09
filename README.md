# DSIW-Project
# Google Landmark Detection Challenge

# Baseline

  Uses KNN landmark detection. Cross platform. Multi threaded.

Dependencies:
1) python 3.6
2) numpy
3) scikit-learn
4) opencv

How to:
1) Download train.csv and test.csv from kaggle competition
2) Download images using script.py (python script.py <*.csv> <folder/>)
3) Run baseline notebook. Contains both opencv KNN implementation and Scikit-learn
  
 # Pytorch transfer learning
 
 Dependencies:
 1) Python 3.6
 2) pytorch
 3) numpy
 4) pillow
 5) torchvision
 6) tqdm
 
 Uses transfer learning with Imagenet model 
 
 How to:
 1) run notebook step0_file_transfer
 2) run notebook step1_Transfer_Learning
 
 # Tensorflow transfer learning
 
 tranfer learning with 
 
 Dependencies:
 1) Python 3.6
 2) tensorflow
 
 How to:
 1) python Transfer_Learning_Tensorflow.py --imagedir='train'
 
 This file will do cross validation.
 
 Note: Refer to tensorflow transfer learning tutorial for more details
 
 # CNN_Pytorch
 
 Uses CNN for landmark detection. Cross platform. Multi threaded. GPU Support (recommended).
 
 Dependencies:
 1) python 3.6 
 2) pytorch
 3) numpy
 4) pillow
 5) pickle
 6) torchvision
 7) scikit-learn
 8) opencv

How to:
1) Download train.csv and test.csv from kaggle competition
2) Download images using script.py (python script.py <*.csv> <folder/>)
3) Run CNN_Pytorch notebook. Change GPU status as needed. Follow any needed instructions inside

Note: Some image files may be corrupt. There is code inside after loading the initial data which will remove those bad images from the dataset. Rerun code above or errors may arise. 

Note: There is an option to save the model and cross validation images for cases where there is an out of memory error. 


# pytorch_CNN
Uses pytorch transfer learning for accuracy

Dependencies: Look at above and PreProcess_CNN and pytorch_CNN

How to: 
1) Download train.csv and test.csv from kaggle competition
2) Download images using fixed_script
3) Preprocess data with PreProcess_CNN
4) Run pytorch_CNN notebook. 

Note: Currently requires GPU


