# 🤖 Linux Command Bot

An AI-driven cybersecurity assistant that helps users **learn, understand, and execute Linux commands** intelligently through a beautiful CLI interface. Powered by Google Gemini AI, this bot doesn't just suggest commands , It explains **how to use them**, **what each flag means**, and **provides real-world examples**. It also assists in debugging by interpreting terminal errors and offering accurate solutions.

---

## 📖 About the Project

**Linux Command Bot** is designed with Linux lovers and cybersecurity enthusiasts in mind. It elevates the learning experience by:

- 🧠 Using **AI to understand natural language questions**
- 🔍 Providing accurate **command syntax**, **options/flags**, and **descriptions**
- 🛠 Suggesting **real examples** to demonstrate usage
- ❗️ Allowing users to **paste terminal errors** and get helpful suggestions
- 🖥 Offering a **beautiful and native CLI experience** using `rich` , `pyfiglet` and `Typer`

This project is entirely **terminal-based**, because we Linux users prefer the keyboard to the mouse. It makes learning and troubleshooting commands **interactive**, **smart**, and **aesthetically pleasing**.

---

## 🛠 Built With

- [Python 3](https://www.python.org/)
- [Google Generative AI (Gemini)](https://ai.google.dev/)
- [Typer](https://typer.tiangolo.com/) – CLI framework
- [Rich](https://rich.readthedocs.io/en/stable/) – beautiful terminal output
- [PyFiglet](https://pypi.org/project/pyfiglet/) – ASCII banners

---
## 📥 Installation & Setup

Follow these steps to install and run the **Linux Command Bot**:

---

### 🔗 1. Clone the Repository

```bash
git clone https://github.com/vethavarshini/Linux_Command_Bot.git
cd Linux_Command_Bot
```
## 🛠️ 2. Create a Virtual Environment

```bash
python -m venv env
```
▶️ Activate the Virtual Environment

Windows (PowerShell):
```bash
.\env\Scripts\activate
```
Linux/Mac:
```bash
source env/bin/activate
```
## 📦 3. Requirements

Before running the bot, install the required Python packages:
```bash
pip install -r requirements.txt
```
## 🔑 4. Add Your API Key
There is already a .env file in the project root.
Open it and add your API key:

GEMINI_API_KEY=<YOUR_API_KEY>

⚠️ Do not share your API key.

## 📦 5. Run the Bot

```bash
python LinuxCommandBot.py
```
✅ Now you're ready to use the Linux Command Bot!


