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
- Trong Project này chúng em sử dụng 4 models chính là: KNeighborsClassifier, RandomForestClassifier, LogisticRegressionClassifier và MLP model. Và RandomForestClassifier cho ra kết quả tốt nhất:
    + RandomForestClassifier cho kết quả tốt với độ chính xác cao và độ chính xác trong việc phân loại cả hai trường     hợp tích cực và tiêu cực.
    + Nó trả về kết quả các chỉ số như accuracy, precision, recall và F1 - Score là tốt nhất.

Tuy nhiên, dựa trên kết quả đánh giá, theo em các mô hình trên vẫn chưa đạt hiệu suất tốt nhất. Nếu được, em sử dụng CNN (Convolutional Neural Network) của thư viện TensorFlow để xây dựng một mô hình tốt hơn tuy nhiên vì một số lí do nên em không đủ thời gian để làm. Vì vậy, nếu phải lựa chọn một mô hình trong bốn mô hình nhóm em đã chọn, RandomForest sẽ là lựa chọn ưu tiên.
