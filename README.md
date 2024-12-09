# **NLP Project: Sentiment Analysis and Language Translation**  

This project explores two essential Natural Language Processing (NLP) tasks: **Sentiment Analysis** and **Language Translation** using state-of-the-art transformer-based models. It leverages the IMDB movie review dataset for sentiment classification and English-to-Spanish translation, demonstrating a robust multilingual text processing pipeline.  

---

## **Table of Contents**  
1. [Project Overview](#project-overview)  
2. [Models and Methodologies](#models-and-methodologies)  
3. [Results and Evaluation](#results-and-evaluation)  
4. [How to Run](#how-to-run)  
5. [Future Improvements](#future-improvements)  
6. [References](#references)  
7. [Video Demonstration](#video-demonstration)  

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
- **Best BLEU Score**: **0.0670 (Sentence 17)**  
- **Challenges**: Low BLEU scores for complex or idiomatic sentences.  

---

---

## **Future Improvements**  

- **Fine-Tuning Models**:  
  - **Objective**: Enhance BLEU scores for complex translations.  
  - **Plan**: Fine-tune MarianMT on domain-specific datasets or more diverse sentence structures.

- **Multilingual Support**:  
  - **Objective**: Expand to other languages.  
  - **Plan**: Utilize multilingual models like mBERT or XLM-R for cross-lingual sentiment analysis and translation.

- **Improved Sentiment Analysis**:  
  - **Objective**: Better handling of sarcasm and mixed sentiments.  
  - **Plan**: Fine-tune more advanced models or use domain-specific datasets to improve sentiment detection.

- **Resource Optimization**:  
  - **Objective**: Improve efficiency of training and inference.  
  - **Plan**: Explore model pruning or distillation to reduce resource usage during training and inference.

---

## **References**  
1. **Vaswani, A. et al. (2017)**  
   - *Attention is All You Need.*  

2. **Devlin, J. et al. (2019)**  
   - *BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding.*  

3. **Lewis, M. et al. (2020)**  
   - *Marian: Fast Neural Machine Translation.*  

4. **Pang, B. & Lee, L. (2005)**  
   - *Seeing Stars: Exploiting Class Relationships for Sentiment Categorization.*  

---

## **Video Demonstration**  

🎥 **Watch the Project Overview Video:**  
[YouTube Project Demonstration](https://www.youtube.com/watch?v=_H-j2MDGID4)

---





