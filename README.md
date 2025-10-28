# Whatsapp-chat-analyzer
A Streamlit-based WhatsApp Chat Analyzer 📊

An interactive web app built with [Streamlit](https://streamlit.io) to analyze your WhatsApp export files. Upload your chat text file and explore interesting statistics like message counts, user activity, word clouds, emojis usage, and more!

Live demo → [[Click here](https://wp-chat-analyzer-1.streamlit.app/)
](https://wp-chat-analyzer-1.streamlit.app/)
---

## 🚀 Features

- Upload exported WhatsApp chat (text format)  
- Visualize total messages, media shared, and link counts  
- See most active users and monthly/weekly trends  
- Generate word clouds of frequently used words  
- Explore emoji usage and top emojis  
- Filter by specific users or time ranges  
- Clean and intuitive UI built with Streamlit

---

## 🧠 How It Works

1. The app parses the chat file, extracts timestamps, users, and message contents.  
2. It cleans data using `preprocessor.py` and uses `helper.py` for analytics logic.  
3. Visualizations created using Pandas, Matplotlib/Seaborn/WordCloud for charts.  
4. Streamlit handles user interface and file upload seamlessly.

---

## 🛠️ Installation & Local Setup

```bash
# Clone this repository
git clone https://github.com/Srija-11/Whatsapp-chat-analyzer.git
cd Whatsapp-chat-analyzer

# Install dependencies
pip install -r requirements.txt

# Run locally
streamlit run app.py

