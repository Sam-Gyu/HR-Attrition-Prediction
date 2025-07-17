# HR Attrition Prediction using Logistic Regression
This project applies **Logistic Regression** to predict employee attrition using a real-world HR dataset.
It includes full data preprocessing, model training, and **classifier evaluation using multiple metrics**.

## Features
- Data Preprocessing
   - Handled categorical variables using `pd.get_dummies()`
   - Scaled numerical features using `StandardScaler`
- Model Training
   - Applied **Logistic Regression** with to train the model on the processed data
- Model Evaluation
   - Generated a **confusion matrix** and visualized it using a **heatmap** with `Seaborn`
   - Calculated key classification metrics:
      - **Precision**: Measures the accuracy of positive predictions
      - **Recall**: Measures how well the model identifies positive cases
      - **F1 Score**: Harmonic mean of precision and recall
- Displayed a **classification report** with precision, recall, F1-score, and support for each class

## Tools
- pandas
- scikit-learn
- seaborn
- matplotlib


