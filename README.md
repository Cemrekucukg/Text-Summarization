# Text Summarization Using RNN and NLP

This project focuses on **text summarization** using **Natural Language Processing (NLP)** techniques and **Recurrent Neural Networks (RNN)**.  
The model is built with **LSTM layers** and an **attention mechanism**, trained on an Amazon reviews dataset that includes both text and summary columns.

## 📘 Overview
The goal of this project is to automatically generate concise and meaningful summaries from longer text inputs without losing context.  
It uses a deep learning approach with an **Encoder-Decoder RNN architecture** implemented in **Keras (TensorFlow)**.

## 📂 Dataset
- **Source:** Amazon Review Dataset  
- **Used Columns:** `Text`, `Summary`  
- **Samples:** ~100,000  
- Only relevant text data was used; unnecessary features were excluded for performance.

## 🧠 Model Details
- **Architecture:** Stacked LSTM (3 layers) + Attention  
- **Optimizer:** RMSProp  
- **Loss Function:** Sparse Categorical Crossentropy  
- **Batch Size:** 128  
- **Validation Split:** 10%  
- **Early Stopping:** patience=5  
- **Epochs:** 50 (stopped at 21)

## 🔍 Results
- The model successfully generated summaries that closely match original dataset summaries.
- Some outputs were identical or nearly identical to the original, proving the model’s learning efficiency.
- Further improvements could be made with more data and longer training.

## 🧰 Technologies Used
- Python  
- JupyterLab  
- TensorFlow / Keras  
- NumPy, pandas, matplotlib  

## 🧑‍💻 Author
**Cemre Küçükgöde**

## 📜 License
This project is for educational and research purposes only.
