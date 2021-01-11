# Kaggle-Riiid-Answer-Correctness-Prediction
 Kaggle Competition: Riiid Answer Correctness Prediction
 
This is my solution (Bronze Medal, top 9%) to the Kaggle competition "Riiid Answer Correctness Prediction"
https://www.kaggle.com/c/riiid-test-answer-prediction

In this competition, my challenge is to create algorithms for "Knowledge Tracing," the modeling of student knowledge over time. The goal is to accurately predict how students will perform on future interactions.
 
 ## Data
 - 100M rows, which is a subset of the open-source ednet data: https://github.com/riiid/ednet
 - Raw features: student_id, question_id, student_answer, elapsed_time, ...
 - Target: Binary label indicating whether the student answers the question correctly
 
 ## Metrics
 - Binary AUC
 
 ## Models
 - LightGBM (see the training and the inference notebook)
 - Neural Network (SAKT, see the inference notebook)
 
 ## Training
 - TBD
 
 ## Results
 - TBD
 
 ## Software package
 - TBD
 
