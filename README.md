
# 🌙 SoulSpace — AI-Powered Emotional Journal & Wellness Companion

SoulSpace is a **mental-well-being application** designed to help you understand your emotions through **daily journaling, AI-based emotion detection, and mood tracking**.
It analyzes your journal entries, stores your emotional patterns, visualizes mood trends, and offers a **supportive chatbot** to talk to.

> ⚠ SoulSpace does **not replace a therapist**. It is meant to support self-awareness and emotional tracking, not clinical treatment.

---

## 💡 Core Features

| Feature                                | Description                                                            |
| -------------------------------------- | ---------------------------------------------------------------------- |
| ✍ AI-powered journal emotion detection | Detect emotions like joy, sadness, fear, anger, etc. from journal text |
| 🔒 Journal storage                     | Entries and emotion scores are saved securely                          |
| 🗓 Mood color-based calendar           | Visual mood summary for each day                                       |
| 📊 Mood chart and graphs               | View mood trends over time                                             |
| 🤖 Emotional support chatbot           | Safe space to talk and reflect                                         |
| 🌱 Wellness resources                  | Meditation, calm music & breathing exercise links                      |

---

## 📂 Project Structure

```
SoulSpace/
├── app.py                        # Main homepage / journaling interface
├── pages/
│   └── chatbot.py                # Chatbot page
├── utils/
│   ├── emotion_detection.py      # Emotion scoring from journal text
│   ├── calendar_utils.py         # Calendar creation & coloring logic
│   └── chart.py                  # Mood analytics plotting
├── emotions_journal.csv          # Auto-generated journal log
├── requirements.txt              # Dependencies
└── README.md
```

---

## 📦 Requirements

These are the package dependencies listed in `requirements.txt`:

```
streamlit
pandas
matplotlib
scikit-learn
textblob
numpy
```

> *(Add/remove items depending on your actual version of requirements.txt — but this format is correct.)*

---

## ▶ How to Run

1. Install dependencies

```
pip install -r requirements.txt
```

2. Launch the app

```
streamlit run app.py
```

3. Make sure the folder structure remains unchanged — `pages/` and `utils/` must remain inside the project directory.

---

## 🧠 Why SoulSpace Matters

Emotions fluctuate daily — and many times we forget *what triggered them*.
SoulSpace provides:

* A safe space to write your thoughts
* An objective analysis of your emotional tone
* A visual record of your moods over time

It helps you understand patterns like:

* What situations bring joy or stress
* Are emotions improving week by week
* Which periods feel overwhelming or peaceful

Awareness is the first step toward healing. 💙

---

## 🧠 Disclaimer

SoulSpace provides emotional reflection and companionship,
but **is not a replacement for professional mental health care**.
Please consult a therapist if you are struggling or in distress.

---

## 👨‍💻 Developer

**Muhammed Rashid**
Passionate about AI applications in emotional well-being, psychology & self-awareness.

---

## 🌟 Future Enhancements

* Weekly & monthly AI mood summaries
* Push notification reminders
* Voice or audio journaling
* Mobile app / PWA
* Encrypted cloud account sync

---

