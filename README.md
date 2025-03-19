Credit Card Fraud Detection 
Overview
This project aims to detect fraudulent credit card transactions using machine learning techniques, specifically the Random Forest algorithm. With the rise in online transactions, credit card fraud has become a significant issue, leading to substantial financial losses. The proposed model improves fraud detection accuracy by classifying transactions as either fraudulent or legitimate.

Objectives
Detect fraudulent transactions using machine learning.
Improve fraud detection accuracy with Random Forest and CART (Classification and Regression Tree) algorithms.
Evaluate model performance based on accuracy, sensitivity, specificity, and precision.
Visualize the results using graphical models.
Dataset
The dataset used contains transaction records, with attributes such as transaction amount and fraud status. The data is preprocessed to remove redundancies and fill missing values before being split into training and testing sets.

System Requirements
Hardware Requirements
Processor: Intel
RAM: 4 GB or more
Hard Disk: 260 GB minimum

Software Requirements
Programming Language: Python
Libraries: NumPy, Pandas, Scikit-learn, Matplotlib
IDE: Jupyter Notebook (via Anaconda)
Operating System: Windows 7, 8, 10 (32-bit or 64-bit)

Steps to Run the Project
To run project double click on ‘run.bat’ file to get below screen
 ![image](https://github.com/user-attachments/assets/28b99b16-fa96-4600-aa46-f54cdeb66611)

In above screen click on ‘Upload Credit Card Dataset’ button to upload dataset
 ![image](https://github.com/user-attachments/assets/b5e74ca7-d746-499f-a0da-2d785ffdf046)

After uploading dataset will get below screen
![image](https://github.com/user-attachments/assets/5038875f-d737-41bd-839a-e54d39cfdcd2)

Now click on ‘Generate Train & Test Model’ to generate training model for Random Forest Classifier
 
![image](https://github.com/user-attachments/assets/da34dd2f-127a-45da-b0a7-d90a3b305194)

In above screen after generating model we can see total records available in dataset and then application using how many records for training and how many for testing. Now click on “Run Random Forest Algorithm’ button to generate Random Forest model on train and test data
 ![image](https://github.com/user-attachments/assets/70f33a23-02ed-4cc3-833c-d47e24c6f644)


In above screen we can see Random Forest generate 99.78% percent accuracy while building model on train and test data. Now click on ‘Detect Fraud From Test Data’ button to upload test data and to predict whether test data contains normal or fraud transaction
 ![image](https://github.com/user-attachments/assets/bde85e85-23e1-492b-b702-b51693a4ef77)

In above screen I am uploading test dataset and after uploading test data will get below prediction details
 ![image](https://github.com/user-attachments/assets/c84a9a9a-2ec9-49b7-acc0-654ae950d107)

In above screen beside each test data application will display output as whether transaction contains cleaned or fraud signatures. Now click on ‘Clean & Fraud Transaction Detection Graph’ button to see total test transaction with clean and fraud signature in graphical format. See below screen
 ![image](https://github.com/user-attachments/assets/bfd44a25-948b-4c72-a66f-75f3e66e2826)

In above graph we can see total test data and number of normal and fraud transaction detected. In above graph x-axis represents type and y-axis represents count of clean and fraud transaction
