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
