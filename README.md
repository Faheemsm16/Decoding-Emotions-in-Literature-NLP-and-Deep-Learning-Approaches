# Decoding Emotions in Literature  
**NLP and Deep Learning Approaches for Literary Emotion Detection**

## Overview
This project presents a novel framework for detecting **fine-grained emotions** in literary texts using **Natural Language Processing (NLP)** and **Deep Learning**. Leveraging **DistilBERT** fine-tuned on the **GoEmotions dataset**, the system identifies nuanced emotional patterns in narratives and visualizes them using **heatmaps** and **emotion evolution graphs**.

> Unlike traditional sentiment analysis, this approach focuses on understanding complex, overlapping emotions in literature such as **remorse**, **caring**, **joy**, and **realization**.

---

## Objectives
- Detect fine-grained emotions in literary texts.
- Compare transformer-based models vs. lexicon-based methods.
- Visualize emotion transitions using heatmaps and line graphs.
- Enable real-time and interpretable emotion profiling in literature.

---

## Technologies Used
| Category         | Tools/Models                           |
|------------------|----------------------------------------|
| Programming      | Python 3.10+                           |
| NLP Framework    | Hugging Face Transformers, NLTK        |
| Model            | DistilBERT (`joeddav/distilbert-base-uncased-go-emotions-student`) |
| Data             | GoEmotions Dataset, Sample Poems       |
| Visualization    | Matplotlib, Seaborn                    |

---

## Methodology

### 1. Preprocessing
- **Tokenization** using DistilBERT tokenizer
- **Stopword removal** (NLTK)
- **Sliding window segmentation**: 20-word windows with 50% overlap

### 2. Emotion Classification
- Multi-label classification using **DistilBERT**
- Baseline comparison using **NRC Emotion Lexicon**

### 3. Visualization
- **Emotion evolution graphs** (line plots)
- **Emotion heatmaps** for segment-level intensity

---

## Results
- **Transformer-based models** outperform lexicon-based methods on subtle, figurative language.
- **Multi-label classification** effectively captures overlapping emotions.
- **Sliding window segmentation** enhances emotional transition tracking.

---

## Sample Output

**Lexicon-Based Analysis**

![image](https://github.com/user-attachments/assets/bc5c5fee-1f1f-4e7f-b4d2-88793c990feb)

**Transformer-Based Emotion Analysis:**

![image](https://github.com/user-attachments/assets/fd98eeca-834f-4ab3-b917-cf84c7acb301)

**Sliding Window Result:**
![image](https://github.com/user-attachments/assets/443d6414-61db-451e-9cf4-1670f7e8666d)

**Emotion Evolution Graph:**
![image](https://github.com/user-attachments/assets/eac3d6f9-9429-4128-857d-fd8a888a0c5c)

**Emotion Heatmap:**
![image](https://github.com/user-attachments/assets/7a6e0c65-bf8a-466a-8dbb-9815a5dece09)


---

## Challenges
- Figurative and symbolic language (e.g., metaphors)
- Emotion co-occurrence and ambiguity
- Sarcasm and irony detection
- Limited performance on archaic or poetic expressions

---

## Future Work
- Fine-tuning on large-scale literary corpora
- Domain-specific emotion lexicons
- Incorporation of **audiobook-based multimodal cues**
- Interactive emotion-based reading tools

---

## Authors
- **Mohammed Farhan S M** – `faheemproject20@gmail.com`  
- **Saranya R P** 
- **Ramya A K**  
- **Vijayalakshmi** (Assistant Professor)  
**Affiliation**: B.S. Abdur Rahman Crescent Institute of Science and Technology

---
