# Mini-Project for Fundamentals of Machine Learning Course
![background](./materials/ai_wp.jpg)
This repository contains the code and data for a mini-project on facial expression recognition using machine learning algorithms.

## 📑 Project Policy
- Team: group should consist of 3-4 students.

    |No.| Student Name    | Student ID |
    | --------| -------- | ------- |
    |1|Nguyễn Minh Khang|21110110|
    |2|Nguyễn Quý Công|21110048|
    |3|Dương Thị Kim Liên|21110119|
    |4|Lê Trọng An|21110235|

- The submission deadline is strict: **11:59 PM** on **June 22nd, 2024**. Commits pushed after this deadline will not be considered.

## 📦 Project Structure

The repository is organized into the following directories:

- **/data**: This directory contains the facial expression dataset. You'll need to download the dataset and place it here before running the notebooks. (Download link provided below)
- **/notebooks**: This directory contains the Jupyter notebook ```EDA.ipynb```. This notebook guides you through exploratory data analysis (EDA) and classification tasks.

## ⚙️ Usage

This project is designed to be completed in the following steps:

1. **Fork the Project**: Click on the ```Fork``` button on the top right corner of this repository, this will create a copy of the repository in your own GitHub account. Complete the table at the top by entering your team member names.

2. **Download the Dataset**: Download the facial expression dataset from the following [link](https://mega.nz/file/foM2wDaa#GPGyspdUB2WV-fATL-ZvYj3i4FqgbVKyct413gxg3rE) and place it in the **/data** directory:

3. **Complete the Tasks**: Open the ```notebooks/EDA.ipynb``` notebook in your Jupyter Notebook environment. The notebook is designed to guide you through various tasks, including:
    
    1. Prerequisite
    2. Principle Component Analysis
    3. Image Classification
    4. Evaluating Classification Performance 

    Make sure to run all the code cells in the ```EDA.ipynb``` notebook and ensure they produce output before committing and pushing your changes.

5. **Commit and Push Your Changes**: Once you've completed the tasks outlined in the notebook, commit your changes to your local repository and push them to your forked repository on GitHub.


Feel free to modify and extend the notebook to explore further aspects of the data and experiment with different algorithms. Good luck.



## Result Report
- In question 3, you asked us to use GridSearchCV for tuning classification, but due to the condition of the device, we could not run many different parameters on the same device, instead we tested it on multiple devices and selected the best parameter to run in the EDA file.
  
- In this project, we use 4 main models: KNeighborsClassifier, RandomForestClassifier, LogisticRegressionClassifier and MLP model. And RandomForestClassifier gives the best results:
    + RandomForestClassifier gives good results with high accuracy and accuracy in classifying both positive and negative         cases.
    + It returns the results of indicators such as accuracy, precision, recall and F1 - Score is the best.

However, based on the evaluation results, in my opinion, the above models have not yet achieved the best performance. If I could, I would use the TensorFlow library's CNN (Convolutional Neural Network) to build a better model, but for some reason, I didn't have enough time to do it. So, if I had to choose one of the four models my group chose, RandomForest would be the preferred choice.
