# **NLP Project: Sentiment Analysis and Language Translation**  

This project explores two essential Natural Language Processing (NLP) tasks: **Sentiment Analysis** and **Language Translation** using state-of-the-art transformer-based models. It leverages the IMDB movie review dataset for sentiment classification and English-to-Spanish translation, demonstrating a robust multilingual text processing pipeline.  

---

## **Table of Contents**  
1. [Project Overview](#project-overview)  
2. [Models and Methodologies](#models-and-methodologies)  
3. [Results and Evaluation](#results-and-evaluation)  
4. [Project Structure](#project-structure)  
5. [How to Run](#how-to-run)  
6. [Future Improvements](#future-improvements)  
7. [References](#references)  
8. [Video Demonstration](#video-demonstration)  

---

## **Project Overview**  

The goal of this project is to automate the analysis and translation of text data, enabling cross-lingual sentiment analysis. The project integrates two tasks:  

1. **Sentiment Analysis**: Classifies IMDB movie reviews into positive or negative sentiments using a fine-tuned **DistilBERT** model.  
2. **Language Translation**: Translates English reviews into Spanish using the **Helsinki-NLP MarianMT** model, enabling better global communication.  

---

## **Models and Methodologies**  

### **1. Sentiment Analysis**  
- **Model**: DistilBERT-based sentiment classifier.  
- **Task**: Binary classification (positive/negative).  
- **Preprocessing**: Tokenization, padding, and truncation.  
- **Training and Evaluation**: Fine-tuned using PyTorch, achieving **89.3% accuracy**.  

### **2. Language Translation**  
- **Model**: Helsinki-NLP MarianMT for English-to-Spanish translation.  
- **Architecture**: Transformer-based Seq2Seq with Attention Mechanism.  
- **Evaluation Metric**: BLEU scores.  
- **Observations**: Accurate translations for simple sentences, with room for improvement in complex sentence structures and idiomatic expressions.  

---

## **Results and Evaluation**  

### **Sentiment Analysis**  
- **Baseline Accuracy (Logistic Regression)**: 82%  
- **Fine-Tuned DistilBERT Accuracy**: **89.3%**  
- **Error Analysis**: Challenges in classifying sarcastic or mixed-tone reviews.  

### **Machine Translation**  
- **Evaluation Metric**: BLEU scores for 20 sample sentences.  
- **Best BLEU Score**: 0.0670 (Sentence 17)  
- **Challenges**: Low BLEU scores for complex or idiomatic sentences.  


