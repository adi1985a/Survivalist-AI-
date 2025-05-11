# Survivalist Pro – Offline Emergency AI Assistant

**An intelligent survival and psychological support assistant powered by OpenAI.**


## Description

**Survivalist Pro** is a conversational AI assistant that combines survivalist expertise with psychological support. It guides users through emergency situations—ranging from urban accidents to remote survival scenarios—by providing actionable survival strategies and mental health guidance. The assistant interacts via chat and evolves based on user input over time, including tracking key status metrics such as hunger, thirst, and fatigue.

## Features

- 🧠 Powered by OpenAI (GPT-3.5-Turbo)
- 🌐 Emergency or offline survival support
- 📊 Visual tracking of user condition (hunger, thirst, fatigue, injuries)
- 🗣️ Contextual psychological support tools
- 🏕️ Adaptive survival techniques (fire, food, shelter, first aid)
- 📱 Phone tools integration advice (offline maps, compass, light, etc.)
- ⏱️ Dynamic condition tracker (auto-decreases over time)
- 🔁 Ongoing conversation memory using OpenAI Chat API

## Requirements

- Python 3.x
- OpenAI API key
- Required libraries:
  - `openai`
  - `gradio`

You can install the required packages with:

```bash
pip install openai gradio
```

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/survivalist-pro-ai.git
   ```

2. Change directory to the project folder:
   ```bash
   cd survivalist-pro-ai
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set your OpenAI API key in the script:
   ```python
   openai.api_key = "your-api-key"
   ```

## Usage

Run the assistant using Python:

```bash
python survivalist_ai.py
```

Once started, the Gradio web interface will open in your browser.

## Project Structure

```
survivalist-pro-ai/
│
├── survivalist_ai.py          # Main script
├── requirements.txt           # Dependencies
└── README.md                  # Project documentation
```

## Assistant Logic Overview

The assistant follows a structured survival plan:

### Step 1: Situation Assessment
- Asks what kind of emergency the user is in
- Distinguishes between urban accidents (calls emergency numbers) and remote survival scenarios

### Step 2: Data Collection
- User's mental and physical condition
- Available items, health, injuries, fears, and allergies
- Environment details (hazards, water, food, shelter)

### Step 3: Survival Action Plan
- Applies psychological support (e.g. jokes, quotes, check-ins)
- Provides first-aid advice based on symptoms
- Suggests meals with local ingredients and minerals
- Offers survival use cases for nearby items
- Guides on fire-building, shelter, navigation, etc.

### Step 4: Status Tracking
- Users can input `STATUS` to update:
  - Hunger (1–10)
  - Thirst (1–10)
  - Fatigue (1–10)
  - Injuries and available items
- Automatically reduces these stats every 2.5 hours

### Step 5: Continuous Motivation
- Encourages exploration for shelter/items
- Uses device tools if available
- Reminds user of skills and techniques

## License

This project is licensed under the **MIT License**.  
See the `LICENSE` file for full legal text.

## Author

**[Adrian Lesniak]**  
Software Developer  


---

> 💡 Designed for scenarios where staying calm, acting smart, and surviving matter most.  
> ⚠️ *For educational use – not a substitute for real emergency services.*
