# Spam Message Detection Using Machine Learning

## 📌 Project Description
This project classifies SMS messages as **spam or ham** using **Natural Language Processing (NLP) and machine learning**. It preprocesses text, extracts features using **TF-IDF**, and trains a **Logistic Regression model**. The dataset is balanced using **SMOTE**, achieving **98% accuracy**. Future improvements include hyperparameter tuning and deployment.

## 📖 Features
- ✅ **Preprocessing:** Cleans text (removes punctuation, converts to lowercase, removes numbers).  
- ✅ **Feature Extraction:** Uses **TF-IDF vectorization** to transform text into numerical format.  
- ✅ **Imbalanced Data Handling:** Applies **SMOTE** to balance spam and ham messages.  
- ✅ **Model Training:** Uses **Logistic Regression** for classification.  
- ✅ **Evaluation:** Provides precision, recall, F1-score, and accuracy metrics.  


## 🚀 How to Run the Project
### 1️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 2️⃣ Run the Spam Detection Model
```bash
python spam_detection.py
```
### 3️⃣ (Optional) Deploy as an API
```bash
python app.py
```

## 🔍 Model Performance
| **Metric** | **Value** |
|------------|---------|
| Accuracy | **98.21%** |
| Precision (Spam) | **94%** |
| Recall (Spam) | **92%** |
| F1-score (Spam) | **93%** |

## 📊 Future Improvements
- 🚀 **Try Different Models**: Naive Bayes, Random Forest, Deep Learning  
- 🚀 **Optimize Performance**: Hyperparameter tuning, feature engineering  
- 🚀 **Deploy the Model**: Create an API using Flask or FastAPI  

## 📌 Dataset Source
The dataset used is the **SMS Spam Collection Dataset**, available on:
- **[Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)**
- **[UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection)**

## 👨‍💻 Author
- 👤 **Ashkan Sheikhansari**  
- 💼 **MSc Artificial Intelligence | Python Developer | ML/AI Engineer**  
- 🔗 **[LinkedIn](https://www.linkedin.com/in/ashkan-sheikhansari/)**  
