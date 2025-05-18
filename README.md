# 🗣️ Vaakpragna - AI Communication Companion

Vaakpragna is an AI-driven platform designed to help users improve public speaking and debate skills through real-time analysis and intelligent feedback. It includes facial gesture tracking, text and audio analysis, and an AI debate partner.

## 🚀 Features

- 🎤 **Live Speech Analysis**: Real-time feedback on speech delivery using facial gesture and audio cues.
- 📝 **Text Analyzer**: Grammar checking, readability score, and structure feedback.
- 🧠 **Debate with AI**: Practice debating with an intelligent AI opponent that evaluates your performance.
- 🧍 **Face Tracking**: Uses `dlib` and `OpenCV` to analyze eye contact, head movement, and engagement.
- 🗃️ **User Profiles**: Track progress and achievements using a local database.
- 🥇 **Gamification**: Earn badges and certificates based on milestones.


## ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Vaakpragna.git
   cd Vaakpragna
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
python main.py

## 🧠 Tech Stack

- **Python**: Flask, OpenCV, dlib, sqlite3
- **Frontend**: HTML/CSS for UI rendering
- **NLP APIs** *(optional)*: Integration with Gemini or OpenAI for enhanced speech/text analysis

---

## 🏅 Milestone System

- 🥉 **Bronze Badge** – Complete **25 debates**
- 🥈 **Silver Badge** – Complete **50 debates**
- 🥇 **Gold Badge + Certificate** – Complete **100+ debates**

---

## 📸 Avatars & Profiles

- Users can **customize their profile** by selecting an avatar.
- Progress tracking includes:
  - Number of debates participated
  - Badges earned
  - Certificate eligibility

