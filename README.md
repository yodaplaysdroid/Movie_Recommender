# Movie Recommender System for MovieLens100K Dataset
Movie Recommender Neural Network System using Basic Keras API


### 1 Dataset Source
MovieLens100K Dataset URL : https://grouplens.org/datasets/movielens/100k/
- After downloaded, Dataset is then extracted into the working directory


### 2 Dependencies
- OS : Linux Kernel 5.15
- Python 3.11
- Numpy 1.23
- Pandas 2.0
- Scikit-Learn 1.2
- Tensorflow 2.12
- CUDA ToolKit 11.8
- cuDNN for CUDA-11 8.6


### 3 Contents

##### i. Python File : Data_Processing.py
Preprocess input raw data to generate train-test sets and other related files for further processes.

##### ii. Python File : Model_Training.py
Training Keras NN Model with the input training set generated earlier and export a .h5 model file.

##### iii. iPython Notebook : test.ipynb
Testing out the model trained earlier using the test dataset.

##### iv. Python File : Recommender.py
Include the whole recommending process from input (User) to a list of Movies. \
Uses the data processed by Data_Processing file and the model generated by Model_Training file.

##### v. Python File : Main.py
Console Based Program to operate the system.