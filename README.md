# Machine Learning Approach for Epileptic Seizure Detection

Epilepsy is the name of a neurological disorder of the human brain, which is characterized by chronic disorders and occurs at random to interrupt the normal function of the brain. The diagnosis and analysis of epileptic seizure is made with the help of Electroencephalography (EEG). In order to detect seizure, it involves the interpretation of long EEG records by the expert physicians, which is time-consuming and need high human efforts. Thus, this study aims to construct an automatic seizure detection system to analyze epileptic EEG signals.

![ep_states(3)](https://github.com/Mirwais-Farahi/Epileptic-Seizure-Detection-using-Machine-Learning-Algorithms/assets/40177381/d5a84b48-1cf8-4bb7-961f-4af205d1030d)

The CHB-MIT Scalp EEG recording of patients is used in this work for the experiment purpose. The Welch Fast Fourier Transform is used to convert time domain features to the frequency domain. The statistical features are extracted respectively in the time domain and frequency domain.  The ANOVA based feature selection is used to deduct variables. The Random Undersampling (RUS) and Synthetic Minority Oversampling Technique (SMOTE) methods are used to solve the data imbalance problem. Four machine learning algorithms, including decision tree classifier (DTC), extra-decision tree classifier (EDTC),
Linear Discriminant Analysis Classifier(LDAC), Quadratic Discriminant Classifier(QDC), Random Forest Classifier (RFC), Gradient Boosting Classifier (GBC), Multi-layer Perceptron Classifier (MLPC), and Stochastic Gradient Descent Classifier (SGDC) are used to classify the data. As a result, the performance of the proposed classifier is 99.48% of accuracy, 99.79% of sensitivity, and 99.17% of specificity. The system might be a helpful tool for doctors to make a more reliable and objective analysis of patient EEG records.

## Requirements
To run the source code files
1. Python
2. Anaconda or Jupyter Notebook

## Results

| Model name         |    Accuracy     |   sensitivity  |
| ------------------ |---------------- | -------------- |
| My EDTC model      |     99.48%      |      99.79%    |

>📋  The published paper from this research project can be found at https://www.ijcseonline.org/full_paper_view.php?paper_id=4799
