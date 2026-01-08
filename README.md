# Clinical-Notes-Classification

# Problem Statement

Healthcare systems generate a large volume of unstructured clinical notes such as diagnosis reports, prescriptions, lab reports, discharge summaries, and progress notes. Manually classifying these notes is time-consuming, error-prone, and inefficient. There is a need for an automated system that can accurately classify clinical notes into appropriate categories using artificial intelligence techniques.

# Objective
	•	To automatically classify clinical notes into predefined medical categories
	•	To apply Natural Language Processing (NLP) techniques for text preprocessing
	•	To design and train a deep learning model for text classification
	•	To evaluate model performance using standard evaluation metrics
	•	To improve healthcare data organization and management

  # Dataset Description

The dataset consists of text-based clinical notes collected from synthetic/public medical sources.
Each record contains:
	•	Text: Clinical note written by a healthcare professional
	•	Label: Category of the clinical note

Categories:
	•	Diagnosis
	•	Prescription
	•	Lab Report
	•	Progress Notes
	•	Discharge Summary

The dataset is stored in CSV format and is preprocessed before training.

# Methodology / Approach
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
	•	The deep learning model successfully classifies clinical notes into multiple categories
	•	The system predicts the category of unseen clinical text
	•	Outputs include:
	•	Accuracy score
	•	Precision, Recall, and F1-score
	•	Example prediction results
