# 27013325_FYP

# Classification of Alzheimer's Disease progression based on brain MRI and Machine Learning


<hr style="border:2px solid black"> </hr>

- This project is based on Jupyter Notebook, Python and Scikit-learn. The data set is ADNI+IXI. Through exploratory data analysis, data preprocessing (RFECV, StandScaler, PCA) and other operations on the data set, and then use SVM (linear), logistic regression, decision tree and random forest classifier to carry out binary classification and multi-classification of the progression of AD. Finally compare and analyze the results. get conclusion.

<hr style="border:2px solid black"> </hr>


## TABLE OF CONTENT
__1. Data structure__

    1. ADNI (Alzheimer’s Disease Neuroimaging Initiative)
    2. IXI (Information eXtraction from Images)
    
__2. Data Processing and Data Visualization__

    2.1 Total data (ADNI + IXI)
    2.2 Divide male and female
    2.3 Stratified sampling
        1. All male data
        2. Male (CN vs. MCI)
        3. Male (CN vs. AD)
        4. Male (MCI vs. AD)
        5. All female data
        6. Female (CN vs. MCI)
        7. Female (CN vs. AD)
        8. Female (MCI vs. AD)
        
__3. Correlation__

    1. Pearson correlation coefficient

__4. Training model - Binary Classifiers__
    
    4.1 Binary Classifier (Male: CN vs. MCI)
        1. SVM (Linear)
        2. Logistic Regression
        3. Decision Tree
        4. Random Forest
        
    4.2 Binary Classifier (Male: CN vs. AD)
        1. SVM (Linear)
        2. Logistic Regression
        3. Decision Tree
        4. Random Forest
    
    4.3 Binary Classifier (Male: MCI vs. AD)
        1. SVM (Linear)
        2. Logistic Regression
        3. Decision Tree
        4. Random Forest
    
    4.4 Binary Classifier (Female: CN vs. MCI)
        1. SVM (Linear)
        2. Logistic Regression
        3. Decision Tree
        4. Random Forest
        
    4.5 Binary Classifier (Female: CN vs. AD)
        1. SVM (Linear)
        2. Logistic Regression
        3. Decision Tree
        4. Random Forest
    
    4.6 Binary Classifier (Female: MCI vs. AD)
        1. SVM (Linear)
        2. Logistic Regression
        3. Decision Tree
        4. Random Forest
        
__5. Training model - Multi-class classifiers__

    5.1 Multi-class classifiers (All male data)
        1. SVM (Linear)
        2. Logistic Regression
        3. Decision Tree
        4. Random Forest
        
    5.2 Multi-class classifiers (All female data)
        1. SVM (Linear)
        2. Logistic Regression
        3. Decision Tree
        4. Random Forest
