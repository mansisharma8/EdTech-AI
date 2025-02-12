# EdTech AI - Topic Modeling for Educational Content

## Overview
This project focuses on applying **topic modeling** to educational content using **Latent Dirichlet Allocation (LDA)** with **Gensim**. The goal is to extract meaningful topics from a collection of educational materials, helping to classify and recommend content effectively.

## Dataset
- **Source:** Collection of educational articles, transcripts, and online course descriptions.
- **Preprocessing:**
  - Tokenization and stopword removal.
  - Lemmatization to standardize words.
  - TF-IDF weighting to enhance relevant words.

## Methodology
1. **Text Preprocessing:**
   - Removed stopwords and performed tokenization using NLTK.
   - Applied lemmatization to reduce words to their base forms.
   - Used **TF-IDF** for feature extraction.

2. **Topic Modeling:**
   - Implemented **Latent Dirichlet Allocation (LDA)** using Gensim.
   - Tuned the number of topics using coherence score evaluation.
   - Visualized topics with **pyLDAvis** for interpretability.

3. **Results & Insights:**
   - Extracted key topics related to **STEM, humanities, language learning, and career skills**.
   - Identified the most common themes in educational content.
   - Developed a framework to classify and recommend content based on extracted topics.

## Technologies Used
- **Programming Languages:** Python
- **Libraries & Tools:** Gensim, NLTK, spaCy, Matplotlib, pyLDAvis
- **Machine Learning Techniques:** Latent Dirichlet Allocation (LDA), TF-IDF, NLP preprocessing

## Future Improvements
- Integrate **BERT-based topic modeling** for improved contextual understanding.
- Expand dataset with **MOOC course descriptions** for broader insights.
- Develop a **content recommendation system** based on topic extraction.

