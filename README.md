## 📌 **Sentiment Analysis on Flip App Reviews: Comparing IndoBERT-base-p1 vs IndoBERT-base-p2**

---

### 🎯 **Project Objective**

This project aims to classify user sentiment from Flip fintech app reviews using two pre-trained Indonesian transformer models **IndoBERT-base-p1** and **IndoBERT-base-p2**. The goal is to compare their performance and identify which model is more effective for real-world sentiment analysis in Bahasa Indonesia.

---

### 🛠️ **Key Steps**

1. **Data Preprocessing**

   * Case folding, cleaning, tokenization, normalization of informal words

2. **Exploratory Data Analysis (EDA)**

   * WordCloud visualization

3. **Data Splitting**

   * 70% training, 20% validation, 10% testing

4. **Model Fine-Tuning**

   * Models: `IndoBERT-base-p1`, `IndoBERT-base-p2`
   * Optimizer: Adam
   * Learning Rate: `3e-6`
   * Batch Size: `32`
   * Epochs: `5`

5. **Evaluation Metrics**

   * Accuracy, Precision, Recall, and F1-score per class

---

### 📊 **Performance Summary**

| Metric          | IndoBERT-p1 | IndoBERT-p2 |
| --------------- | ----------- | ----------- |
| Accuracy (Test) | 85%         | **87%**     |
| Macro F1-Score  | 0.84        | **0.87**    |

* **IndoBERT-p2** shows stronger generalization performance, especially in handling neutral and negative sentiment.
* Suitable for real-world Indonesian sentiment analysis applications.

---

### ✅ **Conclusion**

IndoBERT-base-p2 is more effective than p1 in classifying Flip user reviews with higher accuracy and F1-score, particularly on unseen data. The results support the model’s ability to handle nuanced sentiment in Indonesian language.

---
