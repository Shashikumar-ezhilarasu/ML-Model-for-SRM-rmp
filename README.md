# ML-competetion-SRM


<img width="984" alt="Screenshot 2025-02-26 at 2 46 49 PM" src="https://github.com/user-attachments/assets/e8d58166-3bb3-4722-ae1d-36a028253c9a" />

we were able to achieve a model 98% accuracy 

Random Forest is a great choice for this dataset because:  

### *1. Handles Both Numerical & Categorical Data Well*  
- Your dataset has a mix of categorical (e.g., major, gender, race, work_industry) and numerical (e.g., gpa, gmat, work_exp) features.  
- Random Forest can handle both types without needing extensive preprocessing like scaling (which is needed for models like logistic regression or SVM).  

### *2. Captures Non-Linear Relationships*  
- Admissions decisions are rarely linear (e.g., a high GMAT score doesn’t always guarantee admission, and work experience might matter more for some majors).  
- Random Forest can capture complex interactions between features without manually engineering them.  

### *3. Handles Missing Values & Outliers Well*  
- Unlike models that require strict imputation (e.g., logistic regression), Random Forest can handle missing values internally and is robust to outliers.  

### *4. Reduces Overfitting with Bagging*  
- It creates multiple decision trees on different random subsets of the data and averages their predictions, reducing the risk of overfitting.  

### *5. Provides Feature Importance*  
- It ranks features based on how much they contribute to decision-making.  
- This can help determine which factors (e.g., gmat, gpa, work_exp) influence MBA admissions the most.  

### *6. Works Well with Imbalanced Data*  
- If the dataset has more rejections than acceptances, Random Forest can still perform well by adjusting class weights or using balanced sampling.  





