# 🧠 NLP Project – Sentiment Analysis

## 📚 Description

This project is focused on **Sentiment Analysis** to understand the overall sentiment of product reviews — whether people liked a product or not. It uses a mix of lexicon-based and machine learning-based approaches to detect sentiments, including tools like **VADER**, **TextBlob**, and **custom ML models**.

### 🧑‍💻 Submitted by:
- Shivank Gupta – 2411AI08  
- Aditya Tiadi – 2411AI34  
- Anubhav Kant – 2411AI10  

---

## 🚀 Tasks Performed

- Sentiment analysis using **VADER** (Valence Aware Dictionary and sEntiment Reasoner)
- Preprocessing of text data using NLP techniques
- Training and evaluation of multiple classifiers (like Logistic Regression, SVM, etc.)
- Visualization of sentiment scores and word clouds
- Use of both lexicon-based and supervised ML methods

---

## 🧪 Dependencies

Make sure you have the following Python libraries installed:

```bash
pip install matplotlib nltk numpy pandas scikit-learn spacy tensorflow textblob tqdm vaderSentiment wordcloud
```

> Note: You may also need to download additional NLP corpora for NLTK and spaCy (e.g., `punkt`, `vader_lexicon`, and `en_core_web_sm`).

---

## 📂 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Aditya3815/NLP_Project_Group52.git
   cd NLP_Project_Group52
   ```

2. Open the notebook:
   ```bash
   jupyter notebook NLP_project_group_52.ipynb
   ```

3. Run all cells in order to see preprocessing, sentiment results, and visualizations.

---

## 📊 Results

The notebook produces:

- Sentiment score analysis on product reviews
- Word clouds for visualizing frequent words
- Accuracy reports and classification metrics for trained models

---

## 💡 Tools & Frameworks Used

- Python
- NLTK & spaCy for NLP tasks
- VADER & TextBlob for sentiment analysis
- Scikit-learn & TensorFlow for ML models
- Matplotlib & WordCloud for visualization

---

## 📁 Dataset

This project uses a dataset containing **25,000 product reviews**, stored in a CSV file.

- **Filename:** `CSV_IPR.csv`
- **Description:** The dataset includes product reviews that are used for training, testing, and evaluating the sentiment analysis models.
- **Usage:** Make sure the CSV file is placed in the root directory of the project or update the notebook path accordingly.

---

## 📬 Contact

Feel free to reach out if you have any questions or feedback!
