# Task 5: Topic Modeling on News Articles

**Description:**  
This task involves discovering hidden topics or themes from a collection of news articles using the BBC News dataset. Topic modeling helps uncover patterns in text data without manually labeling categories.

**Dataset:**  
- [BBC News Dataset](https://www.kaggle.com/datasets/): contains news articles from multiple categories (business, politics, tech, entertainment, etc.)
- We used the `title` + `description` columns for analysis.

**Libraries & Tools:**  
- Python, Pandas  
- NLTK (stopwords)  
- Scikit-learn (CountVectorizer, TfidfVectorizer, LDA, NMF)  
- WordCloud for visualization  
- Matplotlib for plotting  

**Steps Performed:**  
1. **Text Preprocessing:**  
   - Lowercasing, punctuation removal, stopword removal  
   - Tokenization (splitting text into words)  

2. **Topic Modeling:**  
   - **LDA (Latent Dirichlet Allocation):** Extracts hidden topics from the Bag-of-Words representation.  
   - **NMF (Non-negative Matrix Factorization):** Used as a comparison with LDA, applied on TF-IDF representation.  

3. **Visualization:**  
   - Displayed the most significant words for each topic.  
   - Word clouds created for each topic to visually represent important keyw

