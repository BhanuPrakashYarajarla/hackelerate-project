# 🗣️ Vaakpragna - AI Communication Companion

Vaakpragna is an AI-driven platform designed to help users improve public speaking and debate skills through real-time analysis and intelligent feedback. It includes facial gesture tracking, text and audio analysis, and an AI debate partner.

## 🚀 Features

- 🎤 **Live Speech Analysis**: Real-time feedback on speech delivery using facial gesture and audio cues.
- 📝 **Text Analyzer**: Grammar checking, readability score, and structure feedback.
- 🧠 **Debate with AI**: Practice debating with an intelligent AI opponent that evaluates your performance.
- 🧍 **Face Tracking**: Uses `dlib` and `OpenCV` to analyze eye contact, head movement, and engagement.
- 🗃️ **User Profiles**: Track progress and achievements using a local database.
- 🥇 **Gamification**: Earn badges and certificates based on milestones.

## 📁 Project Structure

Vaakpragna/

├── features/

│ ├── init.py

│ ├── debate_with_ai.py

│ ├── shape_predictor_68_face_landmarks.dat

│ ├── text_analyzer.py

│ └── video_analyzer.py

│
├── static/

│ ├── images/

│ │ ├── dice.png

│ │ └── vaaklogo.jpg

│ ├── js/

│ │ ├── auth.js

│ │ ├── debate.js

│ │ └── video-analyzer.js

│ └── style.css

│
├── templates/

│ ├── create_new_room.html

│ ├── debate-with-ai.html

│ ├── friend_vs_friend.html

│ ├── index.html

│ ├── leaderboard.html

│ ├── login_signup.html

│ ├── profile.html

│ ├── text-analyzer.html

│ └── video-analyzer.html

│
├── main.py

├── requirements.txt

└── users.db


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
- **Frontend**: HTML/Tailwind CSS for UI rendering
- **NLP APIs** : Integration with Gemini or OpenAI for enhanced speech/text analysis

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

