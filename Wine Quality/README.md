## 🍷 Wine Quality Analysis<br>

This project analyzes the physicochemical properties of wine and builds classification models to predict wine quality. Using a labeled dataset of red and white wines, the project explores relationships between features like acidity, alcohol, and pH, and applies supervised machine learning algorithms to classify wines into quality categories. This can assist wine manufacturers and enthusiasts in identifying high-quality wines based on their chemical profiles.<br>

---

### 📊 Objective

To develop a predictive model that classifies wine quality based on its physicochemical characteristics, enabling early quality estimation during the production process and aiding in quality control.<br?
- Perform EDA on wine data to discover feature relationships.
- Visualize distributions, correlations, and addresses class imbalance using SMOTE.
- Identify key attributes that influence wine quality (like alcohol, acidity, sugar, etc.).

---

### 🧪 Dataset

- 💡 **Records**: ~ 6,597 wine samples
- 🧬 **Features**: 11 numeric physicochemical variables + 1 quality score (0–10)

---

### 📌 Key Features Analyzed

- Fixed Acidity  
- Volatile Acidity  
- Citric Acid  
- Residual Sugar  
- Chlorides  
- Free Sulfur Dioxide  
- Total Sulfur Dioxide  
- Density  
- pH  
- Sulphates  
- Alcohol  
- **Quality** (target variable)

---

### 📈 Visualizations & Insights

- Correlation heatmap to identify multicollinearity
- Bar plots for quality distribution
- Box plots comparing features across quality levels
- Histograms and KDE plots for feature distributions
- Insight: **Alcohol, sulphates, and volatile acidity** showed strongest correlation with wine quality.

---

### ⚙️ Machine Learning Models Used:
K-Nearest Neighbors (KNN)

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Each model was trained and evaluated using accuracy, confusion matrix, and classification metrics to determine the best performer for predicting wine quality.


---

### 🛠 Tools & Libraries

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Jupyter Notebook

---

