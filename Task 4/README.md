# Task 4: Named Entity Recognition (NER)

**Description:**  
This task involves identifying and categorizing named entities such as **people, organizations, and locations** in news articles. The goal is to extract key information from text and visualize it effectively.

**Dataset:**  
- [CoNLL-2003 Dataset](https://www.kaggle.com/datasets)  
- Contains labeled sentences with token-level annotations for named entities.

**Libraries & Tools:**  
- Python, Pandas  
- SpaCy (`en_core_web_sm` and `en_core_web_md`)  
- NLTK (optional, for preprocessing)  
- Displacy (SpaCy visualization tool)  

**Steps Performed:**  
1. **Text Preprocessing:**  
   - Tokenization, lowercasing  
2. **Named Entity Recognition:**  
   - Applied SpaCy models (`en_core_web_sm` and `en_core_web_md`)  
3. **Entity Extraction:**  
   - Extracted entities and categorized them into types such as PERSON, ORG, LOC, DATE, etc.  
4. **Comparison:**  
   - Compared the performance and entity coverage between small and medium SpaCy models  
5. **Visualization:**  
   - Displayed entities using Displacy for interactive visualization in text  

**Outcome:**  
- Successfully extracted named entities from news articles.  
- Compared two SpaCy models to understand differences in entity recognition.  
- Visual representation of entities provides clear insights into the text content.  

