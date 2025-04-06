# Rock vs. Mine Prediction Using Logistic Regression

This is a simple Machine Learning project to classify sonar signals as either **rock** or **mine** using Logistic Regression.

## 🔧 Technologies Used

- Python
- Pandas, NumPy
- scikit-learn
- Jupyter Notebook

## 📁 Dataset

The dataset contains 208 rows and 60 numerical features. The last column (label) is:
- `R` = Rock
- `M` = Mine

## 🔍 Steps Performed

1. **Data Collection & Preprocessing**
   - Loaded and explored dataset
   - Separated features and labels

2. **Train-Test Split**
   - Used `train_test_split()` with stratification

3. **Model Training**
   - Trained a Logistic Regression model

4. **Evaluation**
   - Accuracy on training data: ~83%
   - Accuracy on test data: ~76%

5. **Prediction System**
   - Built a system to predict if the input data is Rock or Mine

## 📈 Accuracy

- Training accuracy: `0.83`
- Testing accuracy: `0.76`

## ✅ Sample Prediction

```python
# Sample input
prediction = model.predict(input_data_reshaped)
print(prediction)

# Output
['M']
The object is Mine
