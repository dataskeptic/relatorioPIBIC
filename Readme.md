# Word Embeddings and Distance Measurement Project

This project focuses on analyzing and comparing various distance measures across different word embeddings using natural language processing (NLP) techniques. The project aims to evaluate the similarity between words using methods like **Cosine Similarity**, **Jaccard Distance**, and **Word Mover's Distance**, with both **lemma** and **stemmed** forms of the words.

## Project Structure

The repository contains the following Jupyter Notebooks:

- **nilc_wordembeddings_distances_lemma_poo.ipynb**: 
  - Utilizes the **NILC word embeddings** (from the NILC project) to compute word distances.
  - Works with **lemmatized** text to maintain root forms of words.
  - Focuses on analyzing word embeddings and distances for various NLP tasks.
  
- **nilc_wordembeddings_distances_steam_poo.ipynb**: 
  - Similar to the above, but this notebook works with **stemmed** words rather than lemmatized forms.
  - Stemming reduces words to their base or root form by removing suffixes, which may yield different distance results.

- **tf_tfidf__tok2vec_jaccard_distances_lemma_poo.ipynb**: 
  - Focuses on computing distances using **TF-IDF** and **tok2vec** representations, specifically on **lemmatized** text.
  - Includes analysis using **Jaccard Distance**, a set-based metric for comparing word similarity.

- **tf_tfidf__tok2vec_jaccard_distances_steam_poo.ipynb**: 
  - Similar to the previous notebook but operates on **stemmed** text rather than lemmatized.
  - Examines the impact of stemming on **TF-IDF**, **tok2vec**, and **Jaccard Distance** calculations.

## Dependencies

To run the notebooks, you'll need the following dependencies installed:

- **Python 3.x**
- **Jupyter Notebook**
- **SpaCy**
- **Scikit-learn**
- **NLTK**
- **Gensim**

Install the required Python libraries using:

```
pip install -r requirements.txt
```


## Project Goals

The main goal of this project is to compare the performance of different word embeddings and similarity measures on both lemmatized and stemmed forms of text. By using a variety of NLP techniques, we aim to:

- Analyze the impact of lemmatization and stemming on distance measures.
- Compare traditional approaches like **TF-IDF** and **tok2vec** with more modern methods such as **word embeddings**.
- Measure similarity between words and evaluate the results for NLP tasks such as text classification, information retrieval, and clustering.
