# 📚 NLP Projects: Sentiment Analysis and Prompt Text Generator

This repository contains two natural language processing projects:
1.🎭 Sentiment Analysis using RNN on IMDB reviews  
2. Prompt Text Generator


---

## 1. 🎭 Sentiment Analysis Using RNN (IMDB Dataset)

### 🧠 Description
A simple RNN-based model trained on the IMDB dataset to classify movie reviews as **positive** or **negative**. It uses TensorFlow/Keras with embedding and recurrent layers.

### 🔨 Features
- Preprocessing with padding and tokenization
- Uses `SimpleRNN`, `Embedding`, and `Dense` layers
- Trained on 25,000 movie reviews
- Allows prediction on custom review input

### 📁 Files
- `RNN_Sentiment_Analysis.ipynb` — complete training, evaluation, and testing notebook

### 🚀 How to Run
```bash
# Recommended: Run in Google Colab
# Or locally with:
pip install tensorflow

Prompt Text Generator using GPT-2
🧠 Description
This project uses GPT-2 to generate creative writing prompts based on a topic or keyword using HuggingFace Transformers and Gradio for UI.

🔨 Features
GPT-2 based text generation

Adjustable max_length, temperature, and top_k

Web UI built with Gradio

NLP preprocessing with tokenizer

📁 Files
Prompt_Text_Gen.ipynb — main notebook with model + UI

Prompt_Text_Gen_Cleaned.ipynb — GitHub-compatible version (cleaned metadata)

🚀 How to Run
pip install transformers gradio
python Prompt_Text_Gen.py  # If exported from notebook
💡 Sample Usage
Prompt Input:
The future of AI in education
Generated Text:

The future of AI in education is promising. Schools are adopting intelligent tutoring systems...
🧰 Requirements
Install dependencies:


pip install tensorflow transformers gradio
📁 Recommended Repo Structure

├── RNN_Sentiment_Analysis.ipynb
├── Prompt_Text_Gen.ipynb
├── Prompt_Text_Gen_Cleaned.ipynb
└── README.md
