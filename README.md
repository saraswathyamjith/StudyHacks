# StudyHacks

**StudyHacks** is an AI-powered study tool built using Flask, SQL, HTML, CSS, and JavaScript. The platform enables users to generate interactive flashcards using the OpenAI API, offering a dynamic and engaging way to study.

---

## 🚀 Features

- 🤖 **AI-Generated Flashcards**: Uses OpenAI's API to turn concepts into flashcards in real-time.
- 👤 **User Authentication**: Login and registration system to manage personalized study sessions.
- 📊 **Activity Tracking**: SQL database to track login events, flashcard generation, and user study history.
- 🎮 **Gamified Study Mode**: Interactive UI built with HTML/CSS/JS for an engaging learning experience.

---

## 🛠️ Tech Stack

- **Backend**: Flask (Python), SQL
- **Frontend**: HTML, CSS, JavaScript
- **AI Integration**: OpenAI API
- **Database**: SQLite or any SQL-compatible engine

---

## 🗂 File Structure Overview

| File/Folder        | Description |
|--------------------|-------------|
| `app.py`           | Main Flask application entrypoint |
| `database.py`      | SQL database setup and user tracking |
| `functions.js`     | Frontend logic for dynamic behavior |
| `create*.html/.css/.js` | Pages for creating flashcards |
| `play.html/.css/.js`    | Flashcard interaction/gameplay |
| `login.html/.css`  | User login interface |
| `register.css`     | User registration styling |
| `startpage.html`   | Landing/home page |
| `test.*`           | Pages and scripts for testing/debugging |
| `TestingPhrases.py`| Predefined study prompts or test phrases |
| `greenpeople.png`, `profile.png` | UI assets |
| `index.html`       | Root HTML file |

---

## 📦 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/studyhacks.git
cd studyhacks
```

### 2.  Set up a virtual environment
python3 -m venv venv
source venv/bin/activate

### 3.  Set up OpenAI key & account for API Usage
