# 📰 Fake News Detection using LSTM & DistilBERT

## 📌 Overview
This project implements a fake news detection system using Natural Language Processing (NLP) and deep learning techniques. It classifies news articles as **Real** or **Fake** based on textual content using both sequence-based and transformer-based models.

---

## ⚙️ Features
- Text preprocessing (cleaning, tokenization, stopword removal, lemmatization)
- Vocabulary creation and sequence encoding
- LSTM-based deep learning model for sequence learning
- DistilBERT-based transformer model for contextual understanding
- Separate training and prediction pipelines
- Model evaluation using accuracy, precision, recall, and F1-score

---

## 📂 Project Structure

```
Fake-News-detection/
│
├── lstm_train.ipynb
├── lstm_predict.ipynb
├── bert_train.ipynb
├── bert_predict.ipynb
├── README.md
```

---

## 🧠 Models Used

### 🔹 LSTM Model
- Embedding layer for word representation  
- LSTM layer for capturing sequential dependencies  
- Fully connected layer for classification  

### 🔹 DistilBERT Model
- Pretrained transformer model  
- Fine-tuned for fake news classification  
- Captures contextual relationships between words  

---

## 🔄 Workflow
1. Data loading and preprocessing  
2. Tokenization and text cleaning  
3. Encoding and padding of sequences  
4. Model training (LSTM / DistilBERT)  
5. Prediction on new data  
6. Performance evaluation  

---

## 📊 Results
- DistilBERT achieved higher accuracy compared to LSTM  
- Transformer model captured better contextual meaning  
- LSTM provided strong baseline performance  

---

## 🛠️ Tech Stack
- Python  
- PyTorch  
- HuggingFace Transformers  
- NLTK  
- Pandas, NumPy  
- Scikit-learn  

---

## ▶️ How to Run

### 1. Clone the repository
```
git clone https://github.com/kirti125/Fake-News-detection.git
```

### 2. Install dependencies
```
pip install -r requirements.txt
```

### 3. Run LSTM model
```
jupyter notebook lstm_train.ipynb
jupyter notebook lstm_predict.ipynb
```

### 4. Run BERT model
```
jupyter notebook bert_train.ipynb
jupyter notebook bert_predict.ipynb
```

---

## 📌 Notes
- Model weights are not included due to size constraints  
- Notebooks may need to be executed locally or in Google Colab  

---

## 💡 Future Improvements
- Improve generalization using larger datasets  
- Deploy as a web application  
- Add real-time fake news detection pipeline  
