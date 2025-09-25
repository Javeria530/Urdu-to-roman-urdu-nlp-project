# Neural Machine Translation – Urdu to Roman Urdu  

This project implements a **Neural Machine Translation (NMT)** system to transliterate **Urdu Ghazals into Roman Urdu** using a **BiLSTM Encoder–Decoder architecture** in PyTorch.  

--------------------------------------------------------------------------------------------------------------------------------------------------------

## 🚀 Project Overview  
- **Objective:** Build a sequence-to-sequence model that translates Urdu text into Roman Urdu transliteration.  
- **Dataset:** [urdu_ghazals_rekhta](https://github.com/amir9ume/urdu_ghazals_rekhta)  
- **Model Architecture:**  
  - Encoder: BiLSTM (2 layers)  
  - Decoder: LSTM (4 layers)  
- **Experiments:** Hyperparameter tuning on embedding size, hidden units, dropout, learning rate, and batch size.  
- **Evaluation Metrics:** BLEU, Perplexity, and Edit Distance (CER/Levenshtein).  
--------------------------------------------------------------------------------------------------------------------------------------------------------

## 📂 Project Structure  
- ├── data/ # Dataset (processed files)
- ├── preprocessing/ # Urdu text cleaning & tokenization
- ├── models/ # Encoder, Decoder, Seq2Seq model code
- ├── experiments/ # Training scripts & hyperparameter variations
- ├── evaluation/ # Evaluation metrics & results
- ├── app/ # Streamlit app for deployment
- └── README.md # Project documentation
--------------------------------------------------------------------------------------------------------------------------------------------------------
##  Requirements  
- Python 3.8+  
- PyTorch  
- NumPy, Pandas  
- SacreBLEU / nltk (for BLEU score)  
- Streamlit (for deployment)
  --------------------------------------------------------------------------------------------------------------------------------------------------------

Install dependencies:  
```bash
pip install -r requirements.txt
