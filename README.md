# MLFinalProject
ML Final Project: Aidan Aug, Alan Zhang, Shreya Wadhwa, Trisha Karani

# Purpose 
The purpose of this project is to create a CNN Classification for ASL Hand Symbols. 

# Files 
Augmentation.ipynb: contains code for loading raw dataset (**handgesturedataset_part1**), preprocessing, and creating augmented dataset with blur, scale, rotate 30 degrees, vertical flip, and translation transformations. Creates **FinalImages** folder with preprocessed and augmented images. Additionally, contains code for applying multiple augmentations to one image, creates **Mult_Augments** folder. 

FiveConvLayerCNN.ipynb: contains code for training and testing AlexNet model on normal images and augmented image dataset, as well as prediction on multiple augmentation dataset. 
FiveConvLayerCNN-Features.ipynb: contains code for training and testing AlexNet model with hand-to-back and convexity features added to linear layer on normal images and augmented image dataset, as well as prediction on multiple augmentation dataset. 

SimpleCNN.ipynb: contains code for training and testing LeNet model on normal images and augmented image dataset, as well as prediction on multiple augmentation dataset. 
SimpleCNN-Features.ipynb: contains code for training and testing LeNet model with hand-to-back and convexity features added to linear layer on normal images and augmented image dataset, as well as prediction on multiple augmentation dataset. 

convexity.py: contains code for determining and saving the convexity feature on raw images. 
HandToBack.ipynb: contains code for determining hand-to-back ratio feature on raw images. 

Final_Project_Submission.ipynb: final jupyter notebook containing code and discussion of findings. 

**FinalImages**: folder of preprocessed normal images and augmented images. 
**Mult_Augments**: folder of images with 0-3 randomly-determined augmentations applied (per image).
**features**: folder of .npy data of features for images. 
**handgesturedataset_part1**: Raw image data of ASL hand symbols for this project. One of five folders from the [Massey University hand symbol dataset](https://www.massey.ac.nz/~albarcza/gesture_dataset2012.html). 
**models**: folder of saved trained models. 
