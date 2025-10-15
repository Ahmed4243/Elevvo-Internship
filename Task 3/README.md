# Task 3: Fake News Detection

**Description:**  
This task involves detecting fake and real news articles based on their text content. The goal is to build a classifier that can distinguish between truthful and misleading news using NLP techniques.

**Dataset:**  
- [Fake and Real News Dataset](https://www.kaggle.com/datasets)  
- Contains labeled news articles as `FAKE` or `REAL`.  

**Libraries & Tools:**  
- Python, Pandas, NumPy  
- NLTK (stopwords, tokenization, lemmatization)  
- Scikit-learn (TF-IDF vectorization, Logistic Regression, SVM)  
- WordCloud for visualization  
- Matplotlib / Seaborn for plots  

**Steps Performed:**  
1. **Text Preprocessing:**  
   - Cleaned title and content  
   - Lowercasing, punctuation removal, stopword removal, lemmatization  
2. **Feature Extraction:**  
   - TF-IDF vectorization of text  
3. **Model Training:**  
   - Logistic Regression and Support Vector Machine (SVM)  
4. **Evaluation:**  
   - Accuracy, F1-score, confusion matrix  
5. **Bonus:**  
   - Created word clouds for fake vs real news to visualize the most common terms  

**Outcome:**  
- Built a classifier capable of distinguishing fake and real news articles.  
- Visualized key terms in fake vs real news, providing insights into common patterns.  
