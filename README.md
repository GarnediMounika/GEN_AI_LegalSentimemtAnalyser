# GEN_AI_LegalSentimemtAnalyser
# ⚖️ Legal Sentiment Analyzer

**Author**: Mounika Garnedi  
**Specialization**: AI & Machine Learning, NLP Applications  
**Project Type**: NLP, Sentiment Analysis, Model Deployment  
**Interface**: Gradio Web App  

---

## 📌 Project Overview

**Legal Sentiment Analyzer** is a fine-tuned NLP application that automatically classifies legal text (such as contract clauses, case summaries, or policy descriptions) into **Positive**, **Neutral**, or **Negative** sentiments.

It uses `DistilBERT`, a transformer-based language model, and was trained on a custom dataset of 1000+ legal samples.

---

## 🎯 Key Features

- ✅ **Trained Transformer Model** (`DistilBERT`) for legal sentiment classification  
- ✅ **Custom dataset** built for legal domain sentiment labels  
- ✅ **Gradio Web App** with shareable public link (no HTML or JS required)  
- ✅ Clean and professional UI for demo and resume projects

---

## 🛠️ Technologies Used

| Component          | Tool / Framework                      |
|-------------------|----------------------------------------|
| Model              | `DistilBERT` via Hugging Face 🤗 Transformers |
| Training           | PyTorch + `Trainer` API                |
| Interface (Web UI) | Gradio                                 |
| Dataset Format     | CSV (1000+ rows)                       |
| Deployment         | Colab + Gradio (via `share=True`)      |

---

## 🧠 How It Works

1. Load and preprocess the dataset (`legal_sentiment_dataset.csv`)
2. Fine-tune DistilBERT on custom sentiment labels
3. Save trained model to `/content/legal_sentiment_model/`
4. Deploy via Gradio with a simple text input interface

---

## 🚀 How to Run the Project

### ✅ Step 1: Clone the Repo

bash
git clone https://github.com/your-username/legal-sentiment-analyzer.git
cd legal-sentiment-analyzer


✅ Step 2: Open LegalSentimentAnalyzer.ipynb in Google Colab
Train and deploy in one click using Colab.

🌐 Try the Web App
⚠️ Gradio links are temporary. Run the final Gradio cell to get a public link like this:

https://mounika-legal-app.gradio.live
Paste the link in browser to test the model live.

# Sample Prediction
Input: The client has consistently breached the contract despite multiple notices.
Output: Sentiment: Negative

📂 Files Included
File	Description
legal_sentiment_dataset.csv	Custom training dataset (1000+ entries)
LegalSentimentAnalyzer.ipynb	Full training + deployment notebook
README.md	This file 📄

👩‍💻 Author
Mounika Garnedi
AI & ML Enthusiast | NLP Developer


✅ Ideal For
Resume & Portfolio Projects

Showcasing applied NLP skills

Interview Demos (live link)

Academic or internship submissions

💡 Future Improvements
Host permanently on Hugging Face Spaces or Render

Add topic tagging (Contracts, Privacy, Liability, etc.)

Expand dataset with scraped court records and judgments


