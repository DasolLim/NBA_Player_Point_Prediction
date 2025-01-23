# 🏀 NBA Player Point Prediction  
**Training an AI Model to Predict NBA Player Points**

---

## 📖 Introduction  

The growing popularity of fantasy basketball has highlighted the need for objective, data-driven strategies to enhance decision-making. Traditional methods often rely on subjective biases and incomplete analysis, leading to unreliable predictions.  

This project develops a **machine learning model** designed to predict player performance thresholds—such as scoring more than 10 or 20 points—while identifying key features influencing these benchmarks. By leveraging historical player statistics (e.g., points scored, games played, shooting efficiency), the model aims to:  

- Minimize subjectivity.  
- Provide actionable insights.  
- Boost predictive accuracy (75–85% expected accuracy).  

Through data collection, preprocessing, and evaluation using **Random Forests** and other algorithms, this system empowers users to enhance their betting strategies with confidence and objectivity.

---

## ⚙️ Methodology  

### Model Development  

The following machine learning algorithms were explored to determine the most effective approach for player performance prediction:  

1. **Linear Regression**  
   - Used as a baseline model due to its simplicity and interpretability.  
   - Logarithmic transformations were applied to account for non-linear data relationships.  

2. **Random Forests**  
   - Chosen for its ability to handle large datasets and model complex feature interactions.  
   - Feature importance scores helped identify the most relevant predictors.  

3. **Gradient Boosting (e.g., XGBoost)**  
   - Used for its iterative refinement of weak learners.  
   - Hyperparameter tuning enhanced its predictive accuracy.

---

### Model Training and Validation  

To ensure robust and reliable predictions, the following protocols were applied:  

1. **Cross-Validation**  
   - A 5-fold cross-validation approach was used to evaluate model performance across multiple data subsets.  

2. **Evaluation Metrics**  
   - Metrics such as precision, recall, F1 score, and accuracy were used to evaluate the model's ability to balance true positives and false positives effectively.  

3. **Hyperparameter Tuning**  
   - Parameters like the number of estimators, maximum depth, and learning rate were optimized through grid search to maximize model performance.

---

## 📊 Visualizations  

### 🔥 Heat Map of Feature Correlations  
![Heat Map](https://github.com/user-attachments/assets/3abe91e8-1edc-4963-96fd-484ee2f128f9)

---

## ✅ Results  

### Linear Regression Results  
![Linear Regression Graph](https://github.com/user-attachments/assets/a7f14641-26fb-4ecf-9510-e0da5e53a148)

### Random Forest Results  
![Random Forest Graph](https://github.com/user-attachments/assets/437d65a2-6874-4211-aae7-b7a82098e083)

### XGBoost Results  
![XGBoost Graph](https://github.com/user-attachments/assets/ee4cbff4-5a30-49c8-89f1-78d1305ab5d6)

---

## 🏆 Example Prediction  

### NBA Player: LeBron James  
Predicted Points Scored:  
![LeBron James Prediction](https://github.com/user-attachments/assets/2900ba20-3465-4fc7-968c-a0fd908075d6)

---

## 📈 Accuracy Results  

### Point Threshold Prediction Accuracy  
![Point Threshold Accuracy](https://github.com/user-attachments/assets/2575bcae-31a3-4fce-8eb7-354f2168feed)

---

## 🚀 How to Run  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/nba-point-prediction.git
   cd nba-point-prediction
   ```  

2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```  

3. **Run the project**  
   ```bash
   python main.py
   ```  

4. **Analyze the results**  
   - Outputs will include heat maps, model predictions, and evaluation metrics.
