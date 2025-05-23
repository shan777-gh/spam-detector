# 📧 Spam Detection Using Machine Learning

This project builds a spam detection system that classifies text messages (SMS) as either **spam** or **ham** (not spam) using a machine learning model trained on the SMS Spam Collection Dataset.

---

## 📌 Project Highlights

- End-to-end pipeline from data loading to model evaluation
- Text preprocessing using TF-IDF vectorization
- Classification using Multinomial Naive Bayes
- Achieved ~96.9% accuracy
- Includes confusion matrix and classification report

---

## 🧠 Tech Stack

- **Python**
- **Pandas** & **NumPy**
- **scikit-learn**
- **Matplotlib** & **Seaborn**

---

## 📂 Dataset

- Dataset: [SMS Spam Collection](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- Contains 5,574 labeled SMS messages
- Two classes: `ham` (legitimate) and `spam` (unwanted)

---

## 📈 Model Performance

| Metric        | Ham       | Spam      |
|---------------|-----------|-----------|
| Precision     | 96%       | 100%      |
| Recall        | 100%      | 77%       |
| F1-Score      | 98%       | 87%       |
| **Accuracy**  | **96.9%** |           |

---

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/spam-detector.git
   cd spam-detector
2. Install dependencies:
   pip install -r requirements.txt
   
3. Run the Jupyter Notebook:
   jupyter notebook spam_detection.ipynb
