# Steam Reviews Sentiment Analysis with Deep Learning

This project applies **deep learning models** to predict whether Steam game reviews are **recommended or not recommended**.

## Dataset
- Used the same dataset as the previous [machine learning project](https://github.com/Emirhanyld/Machine-Learning-on-Steam-Reviews?tab=readme-ov-file).  
- Around **100,000 reviews** from Steam.  
- Binary classification:  
  - **80% Positive (Recommended)**  
  - **20% Negative (Not Recommended)**  

## Features
- Preprocessing of text data (stopword removal, stemming, TF-IDF, embeddings).  
- Models used: **Deep Learning architectures (e.g., LSTM, Dense Neural Networks)**.  
- Evaluation with Accuracy, Precision, Recall, F1-Score, and AUC-ROC.

## Results
You can view the detailed results in the PDF file: [results.pdf](results.pdf)  

## Files
- `dl_steam_reviews.ipynb` → Jupyter Notebook with training and evaluation.  
- `results.pdf` → Model performance comparison.  

## Requirements
- Python 3.x  
- Libraries: tensorflow / keras, scikit-learn, pandas, numpy, matplotlib, nltk  

## Usage
1. Open the notebook:  
   ```bash
   jupyter notebook dl_steam_reviews.ipynb
   ```
2. Run all cells to train models and view results.
