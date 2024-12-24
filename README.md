# **Credit Card Fraud Detection**

## **Project Description**
This project implements a machine learning pipeline to detect fraudulent credit card transactions. Using a Random Forest classifier and Synthetic Minority Oversampling Technique (SMOTE), the system addresses the class imbalance problem and provides accurate detection of frauds. The project includes preprocessing, exploratory data analysis, and performance evaluation using various metrics and visualizations.

---

## **Dataset**
The dataset consists of anonymized credit card transaction data, including both legitimate and fraudulent transactions. It contains:
- **Features**: Numerical values representing transaction attributes.
- **Target Variable**: `Class` (0 for legitimate, 1 for fraudulent).

---

## **Features**
### **1. Preprocessing**
- Handled missing values using the median.
- Split the data into training and testing sets.
- Applied SMOTE to balance the class distribution.

### **2. Model**
- **Algorithm**: Random Forest Classifier.
- Trained the model on resampled data to improve fraud detection.

### **3. Evaluation Metrics**
- Accuracy
- Precision
- Recall
- F1-Score
- Matthews Correlation Coefficient (MCC)
- Confusion Matrix
- Receiver Operating Characteristic (ROC) Curve

### **4. Visualizations**
- Correlation heatmap of features.
- Confusion matrix for predictions.
- ROC curve for model performance.

---

## **Installation**

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/credit-card-fraud-detection.git
