# Learning-to-See-in-the-Dark

#### System Requirements
● TensorFlow 1.15
● Rawpy
● Scipy 1.2.0
1. To run put train_Sony.py, test_Sony.py and NNFL_Driver_Colab.ipynb in the same Directory
2. Edit the dataset path in both .py files according to your need.
3. The naming convention of dataset files
● Starting with “0” for Training Data (230 Unique images)
● Starting with “1” for Testing Data (50 unique images)
● The last 4 digits indicate the exposure time for each image
4. On Colab we can’t get more than 100 images for training.
5. Train_Sony.py will keep saving the trained model in output in Results_Sony Folder as given Saving Frequency With the Number of total epoch till that point as a folder name.
6. test_Sony will save all output of test data in Result/final. Images names will contain epoch number of each saved epoch at saving frequency.

Further Instructions are in NNFL_Driver_Colab.ipynb file
