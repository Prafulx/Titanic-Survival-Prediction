# Titanic Survival Prediction  

This project predicts whether a passenger on the Titanic survived or not using Logistic Regression. The dataset is preprocessed and enriched with engineered features to improve the accuracy of predictions.  

---

## Key Features  
1. **Data Preprocessing**  
   - Missing `Age` values were filled with the median age.  
   - Encoded the `Sex` column into a binary column `IsFemale`.  

2. **Feature Engineering**  
   - Added a new feature `FamilySize`, combining `Parch` (parents/children aboard) and `SibSp` (siblings/spouses aboard).  

3. **Machine Learning Model**  
   - Used Logistic Regression for classification.  
   - Hyperparameter tuning performed using `GridSearchCV` for optimization.  

4. **Scaling**  
   - Standardized numerical features to improve model performance.  

5. **Output**  
   - The final predictions are saved to a CSV file named `titanic_survival_predictions.csv`.  

---

## Prerequisites  
Make sure the following libraries are installed in your environment:  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

You can install these packages using pip:  
conda install pandas numpy matplotlib seaborn scikit-learn
