# Project - CSE561.1 ADVANCED NATURAL LANGUAGE PROCESSING (3) (SPRING25)

This repo include google colab notebooks for nlp class in Isik University.

- to train the model google colab is used.
- colab's notebook are coppied to this directory.
- there are several revisions are made, most succesful ones are uploaded. 


```

├── README.md
├── scripts               # colab-notebooks.
├── models                # each revision models. 
├── results
|   ├── presentation          # a pdf version of the presentation.
|   ├── project paper         # a pdf version of the project's paper.
```
---
## Project Description

A model to convert paragraphs into condensed summaries. Captures key information in an easily understandable and shorter format.

- Architecture: **Seq2Seq** 
- Dataset: **Multi-XScience**
- Framework: **PyTorch**

---


## Model Architecture

- **Encoder**:
  - LSTM layers with embedding layer
- **Decoder**:
  - LSTM layers and FC output layer
- **Seq2Seq Class**:
  - encoder and decoder classes

---

---

## Improvements

- Early stopping added to reduce overfitting
- Bottleneck architecture
- Vocabulary limit for efficiency
- Graph visualization tools added

---


## Conclusion

Despite many efforts the model was unable to generate meaningful summaries.

Key NLP fundamentals like tokenization, embeddings, semantic meaning, and sequence modeling were implemented.

---
