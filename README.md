####Brain Tumor Image Segmentation with UNET#####

0. You can use FSLeyes software to visualize .nii files. 

1. First step is data preprocessing.
	You should make 2D slices of your 3D/4D image.
	That means convert the .nii file to .png.
	I used the file image_converter.py to accomplish that task. (That code is available online: https://github.com/alexlaurence/NIfTI-Image-Converter/blob/master/python/nii2png.py)
	You should preprocess both the training and testing data. 

2. After preprocessing the data. Launch main.py
	 Don’t forget to specify the directories.
