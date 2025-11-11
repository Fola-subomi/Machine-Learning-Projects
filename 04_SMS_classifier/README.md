
# SMS Text Classification (Spam Detection)

## 📘 Overview
This project builds an SMS classification model to detect **spam** or **ham (legitimate)** messages using Natural Language Processing (NLP) and supervised learning. It’s a practical demonstration of text preprocessing and feature extraction with machine learning.

## 📊 Dataset
The dataset contains SMS messages labeled as:
- **spam** — unwanted or fraudulent messages  
- **ham** — legitimate messages  

Source: [FreeCodeCamp - SMS Text Classification](https://www.freecodecamp.org/)

## 🧠 Methodology
1. **Text Cleaning**
   - Removed punctuation, stopwords, and converted all text to lowercase.
2. **Feature Extraction**
   - Applied **TF-IDF vectorization** to transform text into numerical features.
3. **Data Splitting**
   - Split data into 80% training and 20% testing sets.

## 🧩 Model & Training
- Models Tested:
  - Naive Bayes
  - Logistic Regression
  - Support Vector Machine (SVM)
- Best Model: **Multinomial Naive Bayes**
- Evaluation Metrics: Accuracy, Precision, Recall, F1-score

## 📈 Results
- Achieved **~98% accuracy** on the test set.
- Very high precision in spam detection with minimal false positives.

## 🚀 Future Work
- Deploy as a real-time spam filter API.
- Add deep learning approaches using LSTM or BERT.
- Enhance dataset for multi-language SMS classification.

## ⚙️ Installation & Usage
```bash
git clone <repo-url>
cd sms-text-classification
pip install -r requirements.txt
jupyter notebook fcc_sms_text_classification.ipynb
