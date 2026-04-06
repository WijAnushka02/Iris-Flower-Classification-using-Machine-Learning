# My First ML Project

## 📌 Iris Flower Classification using Machine Learning

### 📖 Overview
This project demonstrates a complete machine learning workflow using the Iris dataset. The objective is to classify iris flowers into three categories based on their physical measurements.

---

### 🌸 Dataset
We used the well-known Iris Dataset which includes:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

#### Target Classes:
- Iris Setosa
- Iris Versicolor
- Iris Virginica

---

### ⚙️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

### 🔍 Project Workflow

1. **Data Loading**
    - Imported dataset from online source
    - Structured using Pandas DataFrame
    
2. **Data Exploration**
    - Checked shape, data types, and summary statistics
    - Visualized data using:
        - Violin plots
        - Pair plots
        - Correlation heatmap
        
3. **Data Preprocessing**
    - Split dataset into features (X) and labels (y)
    - Train-test split (80% training, 20% testing)
    
4. **Model Building**
    - Implemented Support Vector Machine using SVC

5. **Model Evaluation**
    - Accuracy score
    - Classification report (Precision, Recall, F1-score)
    - Confusion matrix visualization

6. **Model Saving**
    - Saved trained model using pickle

7. **Prediction**
    - Loaded saved model and predicted new data

---

### 📊 Results
- Achieved high accuracy on test data
- Most predictions were correct with minimal misclassification

---

### 📁 Project Structure
├── MyFirstMLProject.ipynb
├── README.md

---

### 🚀 Key Learning Outcomes
- Understanding ML pipeline
- Data visualization techniques
- Model training and evaluation
- Model persistence using pickle

---

### 🔗 Future Improvements
- Try other algorithms (KNN, Decision Trees)
- Hyperparameter tuning
- Deploy as a web application
