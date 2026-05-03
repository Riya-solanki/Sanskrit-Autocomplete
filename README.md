# Sanskrit Autocomplete using Metrics & Grammar

## Project Overview

This project focuses on building an intelligent **Sanskrit language autocomplete system** that generates grammatically correct and metrically consistent text.

Unlike conventional autocomplete systems that rely only on statistical predictions, this project incorporates:

- **Sanskrit grammar rules (Vyakarana)**
- **Chandas (metrical patterns)**
- **Natural Language Processing (NLP)**

The goal is to create a system that not only predicts the next word but ensures that the generated output follows the **linguistic richness and structural constraints of Sanskrit literature**.

---

## Problem Statement

Sanskrit is a highly structured language with strict:

- Grammatical rules (Sandhi, Samasa, etc.)
- Metrical constraints (Chandas)

Most modern NLP systems fail to handle these constraints, resulting in:

- Grammatically incorrect outputs  
- Loss of poetic structure  
- Poor contextual understanding  

This project addresses these challenges by combining **rule-based and ML-based approaches**.

---

## ⚙️ Key Features

### Grammar-Aware Autocomplete
- Ensures predictions follow **Sanskrit grammar rules**
- Handles word formations and transformations

### Metric (Chandas) Validation
- Maintains poetic structure based on syllable patterns
- Supports classical Sanskrit verse generation

### NLP-Based Prediction
- Uses language modeling techniques for next-word prediction
- Learns contextual patterns from data

### Hybrid Approach
- Combines:
  - Rule-based filtering (grammar + meter)
  - Data-driven prediction (ML/NLP)

---

## How It Works

1. User inputs partial Sanskrit text  
2. NLP model predicts possible next words  
3. Grammar engine filters invalid outputs  
4. Metric validator ensures proper syllable structure  
5. Final suggestions are returned  

---

## 🧱 Project Structure

```bash
Natural_Language/
│
├── data/                     # Sanskrit dataset / corpus
├── models/                   # Trained NLP models
├── grammar/                  # Grammar rules & validation logic
├── metrics/                  # Chandas (meter) validation
│
├── main.py                   # Entry point
├── preprocess.py             # Data preprocessing
├── train.py                  # Model training
├── predict.py                # Autocomplete logic
│
└── README.md
```

---

## Tech Stack

| Category        | Technology / Tool        | Purpose |
|----------------|-------------------------|--------|
| **Language**    | Python                  | Core implementation |
| **NLP**         | NLTK / Transformers     | Language modeling |
| **ML**          | Scikit-learn / PyTorch  | Prediction models |
| **Text Processing** | Regex / Custom Rules | Grammar validation |
| **Data**        | Sanskrit Corpus         | Training dataset |

---

## Installation & Setup

### Prerequisites

- Python 3.x  
- pip  

---

### Steps

#### 1. Clone Repository
```bash
git clone https://github.com/Riya-solanki/Natural_Language.git
cd Natural_Language
```

#### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

#### 3. Run the Project
```bash
python main.py
```

---

## Usage

Example:

Input:
```
रामः वनम्
```

Output:
```
गच्छति
```

(Ensures grammatical correctness + contextual relevance)

---

## Use Cases

- Sanskrit text editors & writing tools  
- Educational platforms for learning Sanskrit  
- AI-based poetry generation  
- Digital preservation of classical literature  
- Research in linguistics & computational Sanskrit  

---

## Why This Project Stands Out

- Combines **Ancient Linguistics + Modern AI**
- Goes beyond prediction → ensures **correctness**
- Integrates **grammar + poetic meter**
- Hybrid system (Rule-based + ML-based)
- Unique focus on **low-resource classical language**

---

