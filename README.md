# 📰 Named Entity Recognition (NER) from News Articles

This project extracts and categorizes **named entities** (people, locations, organizations, dates, etc.) from news articles using **SpaCy**.  

It demonstrates both **rule-based** and **model-based** approaches for entity recognition.  

---

## 📊 Dataset
Recommended Dataset: [CoNLL 2003 NER Dataset (Kaggle)](https://www.kaggle.com/datasets/abhinavwalia95/entity-annotated-corpus)  

⚠️ The dataset is too large to store on GitHub.  
👉 Download separately and place it inside the `data/` folder.  

---

## 🛠️ Features
- Preprocess text from news articles  
- **Rule-based NER**: Using custom patterns (e.g., regex for dates, organizations)  
- **Model-based NER**: Using SpaCy’s pre-trained models (`en_core_web_sm`, `en_core_web_trf`)  
- Compare accuracy and entity coverage across models  
- **Visualization** of entities using SpaCy’s `displacy`  

---

## 🚀 How to Run
Clone repo:
```bash
git clone https://github.com/your-username/News-NER.git
cd News-NER
Install dependencies:

pip install -r requirements.txt
python -m spacy download en_core_web_sm
python -m spacy download en_core_web_trf


Run notebook:

jupyter notebook notebooks/NER_NewsArticles.ipynb
