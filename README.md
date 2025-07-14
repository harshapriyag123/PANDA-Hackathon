# PANDA-Hackathon
# 🧠 MoodMate – Your AI-Powered Emotional Wellness Companion

MoodMate is an AI journaling assistant designed to help students reflect on their emotional well-being. Using natural language processing, it detects emotional tone in daily journal entries and provides personalized suggestions to support mental health.

> “MoodMate isn’t just about journaling—it’s about being heard, even when you can’t explain how you feel.”

---

## Inspiration

Mental health challenges are growing among teens and students, especially in high-stress academic environments. Journaling helps—but many young people don’t know how to articulate what they feel. **MoodMate bridges this gap**, giving students a safe, intelligent space to explore emotions and receive wellness guidance.

---

## What It Does

-  Accepts free-form journal entries  
-  Detects emotions (joy, sadness, fear, anger, love, surprise)  
-  Returns confidence scores for each emotion  
-  Offers personalized self-care tips  
-  Logs journal entries and emotions for trend analysis (CSV-based)

MoodMate is lightweight, intuitive, and designed to support emotional growth in students—without overwhelming them.

---

## 🔗 Try It Now (Google Colab)

Run MoodMate in your browser, no installation needed:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1zMZzyBgYCTznhzMYxENJ79jLB1xJ1QvH?usp=sharing)

---

## 🛠️ Built With

- **Python** – Core backend logic  
- **Gradio** – Lightweight UI for journaling and emotion analysis  
- **Hugging Face Transformers** – `nateraw/bert-base-uncased-emotion` model  
- **Pandas** – Logging and CSV data storage  
- **Google Colab** – For live demo and testing  
- **MoviePy & Pydub** – For demo video narration  
- **Canva & DALL·E** – For UI mockups and visual design  
- **GitHub** – Version control and open-source hosting

---

## 📦 Installation (Local)

To run locally:

```bash
git clone https://github.com/harshapriyag22/moodmate.git
cd moodmate
pip install -r requirements.txt
python app.py
```
This will launch the Gradio interface in your browser.

## How It Works
- Journal entry is passed to a fine-tuned BERT model
- Emotion probabilities are calculated
- Most probable emotion is shown along with a wellness suggestion
- Entries are logged in a CSV for historical trend tracking

## Challenges
- Balancing emotional nuance and model simplicity
- Designing calming, student-friendly UX
- Creating a faceless demo video with emotional connection
- Writing empathetic and personalized self-care suggestions

## What We're Proud Of
- Building a complete wellness AI companion in days
- Combining machine learning, UX, and psychology
- Empowering students to explore and manage emotions independently
- Creating an accessible, low-code solution using Gradio

## Track: Agentic AI
- Theme: AI tools that adapt, act, and assist students
- Built by: Harsha Priya Ganapathy & Sankarraj Subramani
- Status: Submitted to PANDA Hacks 2025 on Devpost

## License
This project is licensed under the MIT License.

## Contact
For questions, collaborations, or feedback:
📧 harshapriyag22@gmail.com

## Final Message
MoodMate is a safe, intelligent space where students can express how they feel, even when they don’t have the words. One journal entry at a time—it helps them grow.