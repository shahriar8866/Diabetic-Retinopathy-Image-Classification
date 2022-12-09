# Diabetic Retinopathy Image Classification
- Develop a CNN model using ResNet50 pretrained CNN model detect Diabetic Retinopathy from the retina images. Image labels are given in the file names. For example:
Label 0: IDRiD_118_-0.jpg
Label 3: IDRiD_001_-3.jpg
- Images are seperated in train and test sets into two groups as Normal and Abnormal:
Normal: Label 0
Abnormal: Label 3 & Label 4
- ROC curve Plotted for the best result and confusion matrix is shown.

# Execution
- Create a conda environment using following command:
  conda create -n eda_test python=3.8

- activate your env using:
  conda activate eda_test
- install ipykernal package using command:
  pip install ipykernel

- Direct to folder /MDD/app and open jupyter notebook "image_classification.ipynb".
- Make sure your Linux-64 supports docker, docker-compose, and curl command.
- Check the terminal path from your application(e.g., jupyter notebook, vscode) to make sure your
  working directory is /MDD/app.
- Execute all the cells in "image_classification.ipynb" file one by one. This notebook will create
  docker and containers for nginx and python application.
- To send a request and get response from python application, open "send_request.ipynb" file and run cells one by one. This file uses a CURL request to process your image and return the name of detected classes.
- ResNet (Residual Network) is a convolutional neural network that democratized the concepts of residual learning and skip connections. This enables to train much deeper models. Also, it is trained on a million images of 1000 categories from the ImageNet database. Supporting 1000 classes increase the chance of getting a closer class detection to the real category of object.
