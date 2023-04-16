# DM-Kaggle_Text_Classification

A Data Mining assignment to build a Naive Bayes classifier for Kaggle Rotten Tomatoes Reviews dataset

**Steps for Execution in Google Colab :**

1. Upload the notebook using File -> Upload notebook
2. Follow the below steps to download the kaggle dataset for execution :
- Download API Credentials from Kaggle Profile (Account -> Create New API token). A "kaggle.json" file will be downloaded.
- Upload "kaggle.json" file to Google Colab.
- Run the following commands in Google Colab : 
  - ! pip install kaggle 
  - ! mkdir ~/.kaggle 
  - ! cp kaggle.json ~/.kaggle/ 
  - ! chmod 600 ~/.kaggle/kaggle.json

3. Run the command "! kaggle datasets download ulrikthygepedersen/rotten-tomatoes-reviews" to download the dataset
4. Run the command "! unzip rotten-tomatoes-reviews" to unzip the file.
5. Run all the code cells

The above instructions are referred from "https://www.analyticsvidhya.com/blog/2021/06/how-to-load-kaggle-datasets-directly-into-google-colab/"
