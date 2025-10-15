
# AI Medical Chatbot (Vision & Voice)

AI Medical Chatbot is an end-to-end, open-source healthcare assistant leveraging multimodal AI for vision, text, and voice. Built using 100% free tools.


## Features

- **Meta Llama3 Vision 90B:** Advanced multimodal LLM for image & text understanding
- **OpenAI Whisper:** Accurate speech-to-text conversion
- **gTTS & ElevenLabs:** Realistic text-to-speech capabilities
- **Gradio App:** Seamless chat interface with vision and voice support


## Technical Architecture

![Technical Architecture](./TECHNICAL%20ARCHITECTURE.png)

## Project Phases and Python Commands

### Phase 1: Brain of the doctor
```
python brain.py
```

### Phase 2: Voice of the patient
```
python patient_query.py
```

### Phase 3: Voice of the doctor
```
python doctor_response.py
```

### Phase 4: Setup Gradio UI
```
python gradio_app.py
```

## 🧭 Clone the Project
To get started, clone this repository to your local machine using **Git**:

```bash
git clone https://github.com/AdritPal08/AI-Medical-Chatbot-Vision-Voice-.git
```
Then navigate to the project directory:
```bash
cd AI-Medical-Chatbot-Vision-Voice-
```
## 🐍 Setting Up a Python Virtual Environment

You can use **Pipenv**, **pip + venv**, **Conda**, or **UV** depending on your preference.

---

### ⚙️ Using Pipenv

1. **Install Pipenv (if not already installed):**
```bash
   pip install pipenv
```
2. **Install Dependencies with Pipenv:**
```bash
   pipenv install
```
3. **Activate the Virtual Environment:**
```bash
   pipenv shell
```

### 🧱 Using pip and venv

1. **Create a Virtual Environment:**
```bash
   python -m venv venv
```
2. **Activate the Virtual Environment:**
- ***macOS/Linux:***
```bash
   source venv/bin/activate
```
- ***Windows:***
```bash
   venv\Scripts\activate
```
3. **Install Dependencies:**
```bash
   pip install -r requirements.txt
```

### 🧬 Using Conda

1. **Create a Conda Environment:**
```bash
   conda create --name myenv python=3.11
```
2. **Activate the Conda Environment:**
```bash
   conda activate myenv
```
3. **Install Dependencies:**
```bash
   pip install -r requirements.txt
```

### ⚡ Using UV (Fast Python Package Manager)

1. **Install UV:**
```bash
   pip install uv
```
2. **Create a Virtual Environment:**
```bash
   uv venv
```
3. **Activate the Virtual Environment:**
- ***macOS/Linux:***
```bash
   source .venv/bin/activate
```
- ***Windows:***
```bash
   .venv\Scripts\activate
```
4. **Install Dependencies:**
```bash
   uv pip install -r requirements.txt
```

## 🤝 **Contributing**
Contributions are welcome! If you have ideas, improvements, or bug fixes, feel free to **open an issue** or **submit a pull request**.

## 📜 **License**
This project is licensed under the **[GNU GENERAL PUBLIC LICENSE Version 3](LICENSE)**.

## ⭐ **Support & Feedback**
If you like this project, don't forget to ⭐ star the repository!

For feedback and inquiries, contact **[LinkedIn](https://www.linkedin.com/in/adritpal/)**.


---
Developed by **Adrit Pal** 🚀

