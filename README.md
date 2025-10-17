🧠 Sentiment Strategy Comparison

A Hybrid Sentiment Analysis Platform — blending Classical Machine Learning with Generative AI reasoning

🌍 Project Overview

This project is all about exploring how different sentiment analysis strategies perform when we mix traditional ML models with modern LLM-based prompt engineering.

I built a tool that takes product reviews and compares how models like Naive Bayes and TextBlob perform against LLM approaches such as Zero-shot, One-shot, Few-shot, and Chain-of-Thought prompting.

The goal was to understand where classical models still outperform LLMs — and to visualize these results interactively using Gradio and Matplotlib.

⚙️ Tech Stack

Languages & Tools: Python, Gradio, Matplotlib

ML Models: TextBlob, Naive Bayes

GenAI Techniques: Prompt Engineering (Zero-shot, One-shot, Few-shot, Chain-of-Thought)

Libraries: Scikit-learn, Pandas, NumPy, Transformers

🔍 What I Built

A comparison system that tests six different sentiment strategies on a dataset of over 1,000 labeled product reviews.

The Naive Bayes model achieved 96.8% accuracy, while LLM-based prompt strategies averaged around 41% accuracy — a huge performance gap that highlights where each approach works best.

An interactive Gradio interface lets users input text, see real-time predictions, and visualize how each model interprets sentiment.

The backend handles data preprocessing, evaluation metrics (precision, recall, F1-score), and generates radar charts, bar graphs, and trend plots for analysis.

🧩 Architecture at a Glance
User Input (Text)
      │
      ▼
Gradio Frontend (Interactive UI)
      │
      ▼
Backend (Python)
 ├── Text Preprocessing
 ├── Naive Bayes + TextBlob
 ├── LLM Prompt Strategies
 └── Evaluation Metrics
      │
      ▼
Matplotlib Visualizations → Comparison Charts

📊 Results
Strategy	Accuracy	Type
Naive Bayes	96.8%	Classical ML
TextBlob	85.3%	Lexicon-based
Zero-shot	42.7%	LLM
One-shot	40.9%	LLM
Few-shot	43.5%	LLM
Chain-of-Thought	38.4%	LLM Reasoning
💻 How to Run

Clone the repository

git clone https://github.com/<your-username>/Sentiment-Strategy-Comparison.git
cd Sentiment-Strategy-Comparison


Install the required dependencies

pip install -r requirements.txt


Run the Gradio interface

python app.py


Open the link in your browser and start testing sentences interactively.

🖼️ Features

✅ Compare classical ML vs. LLM performance in one place
✅ View real-time predictions for any text input
✅ Explore visual insights with radar and bar charts
✅ Learn how prompt design affects LLM performance
✅ Get a hands-on feel of backend + frontend + GenAI integration

🧠 Skills Demonstrated
Area	What I Did
Backend	Built ML pipelines, evaluation logic, and data processing
Frontend	Designed an interactive Gradio web app
LLM & GenAI	Created Zero-shot, One-shot, Few-shot, and CoT prompts
Visualization	Generated detailed Matplotlib charts for analysis
🚀 Future Improvements

Integrate LangChain for smarter prompt orchestration

Add multilingual support

Deploy with FastAPI + Streamlit hybrid interface

Compare with advanced transformer models like BERT or RoBERTa

