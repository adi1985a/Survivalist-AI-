# 🧭 Survivalist Pro – Offline Emergency AI Assistant

An intelligent survival and psychological support assistant powered by OpenAI for use in emergencies and remote survival scenarios.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Language: Python](https://img.shields.io/badge/Language-Python-blue.svg)](https://www.python.org/)
[![Platform: Cross-platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg)](https://www.python.org/downloads/)

---

## 🧠 Overview

**Survivalist Pro** is an AI-powered assistant that combines survival knowledge with psychological resilience tools. Designed for both online and offline use, it helps users assess their situation, receive survival tips, track key vitals, and maintain mental clarity during emergencies — whether in an urban disaster or stranded in the wild.

---

## ✨ Features

- 🧠 Powered by OpenAI (GPT-3.5-Turbo)
- 🌐 Works in emergency or offline environments
- 📊 Visual tracking of survival stats: hunger, thirst, fatigue, injuries
- 🗣️ Provides psychological support and mental health tips
- 🏕️ Gives adaptive survival techniques (fire, food, shelter, first aid)
- 📱 Advises on phone tool usage: compass, flashlight, offline maps
- ⏱️ Time-based auto-decrease of condition stats
- 🔁 Supports evolving conversation context via OpenAI Chat API

---

## ⚙️ Requirements

- Python 3.x
- OpenAI API Key

### 📦 Python Libraries

Install the required packages:

```bash
pip install openai gradio
```

---

## ▶️ Installation & Usage

### 📥 Clone this repository:

```bash
git clone https://github.com/yourusername/survivalist-pro-ai.git
cd survivalist-pro-ai
```

### 📚 Install dependencies:

```bash
pip install -r requirements.txt
```

### 🔑 Set your OpenAI API key in the script:

```python
openai.api_key = "your-api-key"
```

### 🚀 Run the assistant:

```bash
python survivalist_ai.py
```

Once started, a **Gradio web interface** will launch in your browser.

---

## 📁 Project Structure

```
survivalist-pro-ai/
├── survivalist_ai.py       # Main script logic
├── requirements.txt        # Dependency list
└── README.md               # Documentation
```

---

## 🧩 Assistant Logic Overview

The assistant operates in **five strategic stages**:

### 1️⃣ Situation Assessment

- Asks for the type of emergency
- Differentiates between urban and wilderness scenarios
- Suggests calling emergency services if relevant

### 2️⃣ Data Collection

- Monitors mental and physical state
- Tracks items, injuries, fears, allergies
- Gathers environmental information (e.g. water sources, dangers)

### 3️⃣ Survival Action Plan

- Offers jokes, motivational quotes, and emotional check-ins
- Provides first-aid steps based on symptoms
- Suggests recipes using local ingredients
- Gives instructions for fire-making, shelter, water collection, etc.

### 4️⃣ Status Tracking

Users can update condition stats by typing `STATUS`. Tracks:

- Hunger (1–10)
- Thirst (1–10)
- Fatigue (1–10)
- Injuries and inventory

Condition stats auto-decrease every **2.5 hours** to simulate time passage.

### 5️⃣ Continuous Motivation

- Encourages search for resources
- Recommends using phone sensors if available
- Reminds users of survival tactics and previous steps

---

## 🖼️ Screenshots / Demo

_Coming soon!_  
Once available, place a `.gif` or `.png` in the `/screenshots` folder and reference it like this:

```markdown
![Survivalist Pro Demo](screenshots/demo.gif)
```

---

## 📃 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).  
See the `LICENSE` file for full legal details.

---

## 👤 Author

**Adrian Lesniak**  
Software Developer & AI Enthusiast

---

> 💡 Designed for scenarios where staying calm, acting smart, and surviving matter most.  
> ⚠️ **Note**: For educational and prototyping purposes only — not a replacement for real emergency services.
