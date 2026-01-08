# Project Title :

Clinical Notes Classification Using Deep Learning

# Problem Statement :

Healthcare systems generate a large volume of unstructured clinical notes such as diagnosis reports, prescriptions, lab reports, discharge summaries, and progress notes.
Manually classifying these notes is time-consuming, error-prone, and inefficient.
There is a need for an automated system that can accurately classify clinical notes into appropriate categories using artificial intelligence techniques.





# Objective :
The objective of this project is to develop a deep learning–based system that automatically classifies clinical notes into predefined medical categories using Natural Language Processing techniques. The system aims to improve the efficiency and accuracy of managing unstructured clinical text data.

 
 
 
 
 
 
 
 # Dataset Description:
The dataset used for this project is a synthetic clinical notes dataset created for academic purposes. It contains clinical text records and their corresponding labels for classification.

File name: clinical_notes_dl.csv

Format: CSV

Type: Text-based clinical notes

Classes: Diagnosis, Prescription, Lab Report, Progress Notes, Discharge Summary

The dataset is included in the GitHub repository since the file size is small. All data was preprocessed before training the deep learning model


# Methodology/Approach
1.	Load the clinical notes dataset
2.	Perform text preprocessing (lowercasing, removing special characters, extra spaces)
3.	Encode target labels using Label Encoding
4.	Convert text into numerical sequences using Tokenization
5.	Apply padding to ensure uniform input length
6.	Train a Bidirectional LSTM deep learning model
7.	Evaluate the model using accuracy and classification report
8.	Save the trained model for future predictions

# Steps to Run the Project
1.	Install required libraries
  code: pip install pandas numpy tensorflow scikit-learn joblib
2.	Place the dataset file (clinical_notes_dl.csv) in the project folder
3.	Run the Python script
4.	The model will train and display accuracy and evaluation metrics
5.	The trained model will be saved locally
6.	Use the prediction function to classify new clinical notes

# Results / Output
The deep learning model was successfully trained to classify clinical notes into predefined medical categories. The Bidirectional LSTM model learned meaningful patterns from textual clinical data after preprocessing and tokenization.

