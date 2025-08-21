# 🤰 MaatriCare (মাতৃCare)

**MaatriCare** is an AI-powered maternal health assistant designed for pregnant women in Bangladesh and Bengali-speaking communities. The app offers personalized pregnancy guidance, health tracking, nutrition planning, and emergency support.

---

## 🌟 Features

- **AI Health Assistant**
  - Conversational interface in English
  - Personalized recommendations based on pregnancy stage
  - Symptom evaluation & risk assessment
- **Pregnancy & Postpartum Care**
  - Week-by-week pregnancy tracking
  - Automated ANC appointment scheduling
  - Nutrition plans with local foods
  - Postpartum guidance for mother & newborn
- **User-Friendly Interface**
  - Modern Streamlit dashboard
  - WhatsApp-style chat interface
  - Quick actions for common requests

---

## 🖥️ Dashboard Preview

![Dashboard Screenshot](https://github.com/SadiaShakiba/MaatriCare/blob/cc75481008cc4f9bee54ba7054b04d0ed6531878/Screenshot%202025-08-21%20161210.png)

---

## 🛠️ Tech Stack

- **Backend:** Python 3.10+, LangChain, LangGraph  
- **Frontend:** Streamlit with custom CSS  
- **AI:** Groq API for LLM functionality  
- **State Management:** LangGraph state machines  
- **Logging:** Structured logs for debugging

---

## 🚀 Getting Started

### Prerequisites
- Python 3.10+
- Git
- GROQ API key (for AI functionality)

### Installation

```bash
git clone https://github.com/SadiaShakiba/MaatriCare.git
cd MaatriCare

# Windows
python -m venv maatricare-venv
maatricare-venv\Scripts\activate

# Linux / Mac
python3 -m venv maatricare-venv
source maatricare-venv/bin/activate

pip install -r requirements.txt
````

Create a `.env` file in the root folder:

```
GROQ_API_KEY=your_groq_api_key_here
```

Run the app:

```bash
python main.py
```

The dashboard will be available at [http://localhost:8501](http://localhost:8501).

---

## 📋 Usage

1. Create a profile (LMP date, age, optional medical history).
2. Chat with the AI for health queries, nutrition advice, or appointment scheduling.
3. Use quick action buttons for common tasks.

---

## ⚠️ Disclaimer

This tool provides **supportive guidance only**.
It **does not replace professional medical advice**.
Always consult qualified healthcare providers for health decisions.
  

Do you want me to do that next?
```
