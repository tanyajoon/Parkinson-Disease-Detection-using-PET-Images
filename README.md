# Parkinson Disease Detection using PET Images


# Execution Flow


## Dataset preparation 

1.	Acquire data set (*.nii files) from [PPMI](http://www.ppmi-info.org/)
2.	Acquire the label files (*.csv file)
3.	Update the 'dataPath' variable (if placed somewhere else) 
4.	Run the dataset preparation file using python3 and Jupyter Notebook.




## Dataset preprocessing

FSL is used for preprocessing purposes, for a guide on how to install and use FSL please refer to [installation](https://github.com/tanyajoon/UAlberta-Multimedia-Master-Program---Parkinson-Disease-Detection-using-PET-Images/blob/master/Installation.md) guide.
After successful installation, execute the files using python3 and Jupyter Notebook. The files(*.nii) can be visualized using FSL eyes.

## Testing and Training:

Before executing the testing and training steps please refer to [installation](https://github.com/tanyajoon/UAlberta-Multimedia-Master-Program---Parkinson-Disease-Detection-using-PET-Images/blob/master/Installation.md) guide and install the required modules.
The 3 models (SVM, RF, CNN ) can be executed using the files provided under the Models folder.
## CNN
After aquiring the data (data.csv) open Model_CNN.ipnyb adn Model_CNN Kfold file found in tghe Model folder.
## SVM
After aquiring the related data (Data.csv) open Model_SVM.ipnyb file found in tghe Model folder.
## SVM
After aquiring the related data (Datacnn.csv) open Model_random forest.ipnyb file found in tghe Model folder.
## Demo Video:
A video guide on how this project works and some general guidelines are available in the following youtube link:
[Youtube](https://youtu.be/-wREIi7myDw)
