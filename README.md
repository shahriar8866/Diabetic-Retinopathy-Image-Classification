# Diabetic Retinopathy Image Classification
- Develop a CNN model using ResNet50 pretrained CNN model detect Diabetic Retinopathy from the retina images. Image labels are given in the file names. For example:  
Label 0: IDRiD_118_-0.jpg\
Label 3: IDRiD_001_-3.jpg
- Images are seperated in train and test sets into two groups as Normal and Abnormal:\
Normal: Label 0\
Abnormal: Label 3 & Label 4
- ROC curve Plotted for the best result and confusion matrix is shown.

# Execution
- Create a conda environment using following command: ``conda create -n <Select a Name for your Conda Env> python=3.8``
- activate your env using: `conda activate <Your Conda Env Name>`
- install ipykernal package using command: `pip install ipykernel`
- Direct to folder /Diabetic-Retinopathy-Image-Classification and open jupyter notebook "Diabetic-Retinopathy-Image-Classification.ipynb".
- Execute all the cells in "Diabetic-Retinopathy-Image-Classification.ipynb" file one by one. This notebook will create the data hierarchy of training and testing folder containing normal and abnormal images for each created folder.

