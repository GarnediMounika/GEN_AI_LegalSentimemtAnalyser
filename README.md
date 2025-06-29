# GEN_AI_LegalSentimemtAnalyser
# ⚖️ AI Legal Sentiment Analyzer

A full-stack AI-powered web application that automates the **sentiment analysis of legal documents**, such as contracts, case summaries, and client feedback. Built using cutting-edge NLP models like `FLAN-T5`, `BERT`, or `Mistral`, this tool helps law firms and compliance teams quickly evaluate tone and implications in legal text.

## 🚀 Features

- 🔍 **Sentiment Classification**: Detect whether the input legal text is *Positive*, *Neutral*, or *Negative*.
- 🧠 **Foundation Model Powered**: Uses pre-trained models like FLAN-T5 or Mistral for zero/few-shot performance.
- 📄 **Optional Summarization**: Generates a short summary explaining the sentiment.
- 🌐 **Full-Stack Web Interface**: Includes a responsive frontend and a Flask backend served from Google Colab.
- ⚡ **Rapid API Response**: Real-time classification with ngrok tunnel for public access.
- 📝 **Easy Deployment**: No installation required—everything runs from a Colab notebook and a static HTML page.

## 🧪 Use Cases

- 📁 **Law Firms**: Automate tone-checking in contracts and case notes.
- 🧾 **Compliance Teams**: Flag negative sentiment in legal correspondence.
- 💬 **Client Feedback Analysis**: Understand client tone in legal communications.

## 📥 Input Format

You can provide the legal text:
- Via a **text box** in the web UI
- (Coming soon) Upload `.txt` or `.csv` documents

**Example Input:**  "The client’s tone was aggressive and accusatory regarding the non-compliance of clause 7B in the service agreement."

**Example JSON Response:**
json
{
  "sentiment": "Negative",
  "confidence": 0.91,
  "summary": "Expresses frustration over non-compliance of contractual obligations."
}


🧰 Tech Stack
Layer	Technology
👨‍💻 Backend	Python, Flask, Hugging Face Transformers
🌐 Frontend	HTML, CSS, JavaScript (Vanilla)
⚙️ Models	FLAN-T5, BERT, or Mistral (via Transformers)
☁️ Hosting	Google Colab + Flask + ngrok

🔧 Setup & Run Instructions
▶️ Step 1: Run the Backend on Google Colab
Open the provided Colab Notebook

It:

Loads the pre-trained sentiment model

Spins up a Flask server

Exposes it via ngrok at a public URL (like https://abc123.ngrok.io)

You’ll see your API endpoint in the Colab output

🌐 Step 2: Use the Frontend
Open the index.html file in your browser

Paste your legal text and click Analyze

The result appears with:

📌 Sentiment label

🧠 Summary (optional)

⏱️ Response time

📂 Project Structure
bash
Copy
Edit
├── README.md
├── ai_legal_sentiment_analyzer.ipynb  # Colab backend
├── static/
│   └── style.css                      # Styling
├── templates/
│   └── index.html                     # Frontend UI
└── app.py                             # Flask API (for local runs)
💡 Sample Prompts Used
Few-shot prompt examples used for FLAN-T5:

mathematica
Copy
Edit
Classify the sentiment of the following legal sentence as Positive, Neutral, or Negative:
"The clause in the agreement is unfair and burdensome." → Negative
"The parties agree to collaborate on the joint venture." → Positive
📈 Future Enhancements
📎 File Upload Support (.txt, .docx)

📊 Dashboard for bulk document analysis

🛡️ Authenticated API for secure legal deployment

🌍 Multilingual Legal Text Support

🧑‍💼 Author
Mounika Garnedi
🎓 B.Tech CSE (AI & ML)
💼 Passionate about NLP, Deep Learning, and Building Real AI Products
🌐 LinkedIn | GitHub

📄 License
This project is licensed under the MIT License.

🙌 Acknowledgments
Hugging Face Transformers

Google Colab

IBM watsonx.ai (optional Prompt Lab)

