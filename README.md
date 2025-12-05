# 🧠 Neural Machine Translation (English → French)

This project implements a **Neural Machine Translation (NMT)** system that translates **English sentences to French** using a custom dataset.

The model is based on **Helsinki-NLP/opus-mt-en-fr**, a pre-trained MarianMT transformer, which is then **fine-tuned** on your dataset for improved domain performance.

This repository contains:
- Training script  
- Fast evaluation script  
- Inference (translation) function  
- Preprocessing and dataset instructions  

---

## 📁 Dataset Format

Provide a `.txt` file where **each line contains an English sentence and its French translation**, separated by a **TAB**:

