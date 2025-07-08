🏥 Disease Prediction System
A comprehensive machine learning system that predicts diseases based on symptoms using multiple algorithms including SVM, Naive Bayes, Random Forest, Decision Trees, and Voting Classifier.


🎯 Overview
This system transforms medical knowledge from the Columbia University Disease-Symptom Knowledge Base into a machine learning-powered disease prediction tool. It can analyze symptom combinations and predict the most likely diseases with confidence scores.
Key Features

✅ Multi-Model Prediction: Uses 5 different ML algorithms
✅ Ensemble Learning: Voting classifier combines multiple models
✅ Interactive Interface: User-friendly prediction system
✅ Fuzzy Symptom Matching: Handles various symptom name formats
✅ Confidence Scoring: Provides prediction confidence levels
✅ Top-K Predictions: Shows multiple possible diseases
✅ Educational Tools: Disease information and comparison functions
✅ Advanced Analysis: Symptom frequency and disease complexity analysis




🏥 Disease Prediction System
A comprehensive machine learning system that predicts diseases based on symptoms using multiple algorithms including SVM, Naive Bayes, Random Forest, Decision Trees, and Voting Classifier.
Show Image
Show Image
Show Image
Show Image
🎯 Overview
This system transforms medical knowledge from the Columbia University Disease-Symptom Knowledge Base into a machine learning-powered disease prediction tool. It can analyze symptom combinations and predict the most likely diseases with confidence scores.
Key Features

✅ Multi-Model Prediction: Uses 5 different ML algorithms
✅ Ensemble Learning: Voting classifier combines multiple models
✅ Interactive Interface: User-friendly prediction system
✅ Fuzzy Symptom Matching: Handles various symptom name formats
✅ Confidence Scoring: Provides prediction confidence levels
✅ Top-K Predictions: Shows multiple possible diseases
✅ Educational Tools: Disease information and comparison functions
✅ Advanced Analysis: Symptom frequency and disease complexity analysis

📊 Supported Models
ModelDescriptionUse CaseSVM (Support Vector Machine)Finds optimal decision boundariesComplex symptom patternsGaussian Naive BayesProbabilistic classificationFast predictions, simple casesRandom ForestEnsemble of decision treesRobust, handles overfittingDecision TreeInterpretable tree-based decisionsUnderstanding decision logicVoting ClassifierCombines all modelsBest overall performance
🚀 Quick Start
Prerequisites
bashPython 3.8+
Jupyter Notebook
Installation

Clone or download the notebook

bash# If using git
git clone <repository-url>
cd disease-prediction-system

Install required packages

bashpip install numpy pandas scikit-learn matplotlib seaborn jupyter openpyxl

Download the dataset

Visit: https://people.dbmi.columbia.edu/~friedma/Projects/DiseaseSymptomKB/index.html
Download the disease-symptom knowledge base
Save as data/raw_data.xlsx


Create directory structure

disease-prediction-system/
├── disease_prediction_notebook.ipynb
├── data/
│   └── raw_data.xlsx
├── models/                 # Auto-created for saved models
└── README.md
Running the System

Start Jupyter Notebook

bashjupyter notebook

Open the notebook

Open disease_prediction_notebook.ipynb


Run all cells

Execute cells 1-20 in sequence
The system will automatically train models and save them



📖 Usage Guide
Basic Prediction
python# Predict disease from symptoms
symptoms = ['chest pain', 'shortness of breath', 'dizziness']
result = predict_disease(symptoms, 'VotingClassifier')
display_prediction_results(result)
Output:
🏥 DISEASE PREDICTION RESULTS
════════════════════════════════════════════════════════════
🔍 Input Symptoms: chest pain, shortness of breath, dizziness
✅ Matched Symptoms (3): pain chest, shortness of breath, dizziness
🎯 PRIMARY PREDICTION: hypertensive disease
📊 Confidence: 0.892
🤖 Model Used: VotingClassifier
📋 TOP 5 PREDICTIONS:
 1. hypertensive disease           (0.892)
 2. coronary arteriosclerosis      (0.067)
 3. myocardial infarction          (0.023)
 4. heart failure                  (0.012)
 5. arrhythmia                     (0.006)
