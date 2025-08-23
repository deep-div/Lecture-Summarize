# 📘 Lecture Summarizer

![screenshot](https://github.com/user-attachments/assets/35abd353-680d-4b1f-96f6-152bb7b6c75a)

**Lecture Summarizer** is a streamlined tool designed to automatically convert lecture audio into concise, structured summaries. By leveraging state-of-the-art speech-to-text and natural language processing models, this tool enhances productivity for students, educators, and professionals who rely on spoken content.

--- 

## 🔍 Overview 

This tool allows users to:

* Convert audio recordings of lectures into accurate transcripts using models such as **OpenAI Whisper** or **Google Gemini**.
* Automatically generate clean, coherent summaries of those transcripts.
* Extract key points, bullet lists, and highlight important insights for easy reference.

---

## 🧠 Core Technologies

* **Audio-to-Text Conversion**:

  * [OpenAI Whisper](https://openai.com/research/whisper): Robust and open-source ASR model for multilingual speech recognition.
  * [Google Gemini](https://deepmind.google/technologies/gemini/): State-of-the-art model offering multimodal capabilities, including transcription.

* **Text Summarization**:

  * Custom summarization pipeline using LLMs or fine-tuned transformer-based models (e.g., BART, T5).
  * Optionally includes keyword extraction and topic segmentation.

---

## 🛠️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/deep-div/Lecture-Summarize.git
cd lecture-summarizer
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Add API Keys (if using OpenAI or Gemini)

Create a `.env` file:

```
OPENAI_API_KEY=your_openai_key
GOOGLE_API_KEY=your_google_key
```

---

## 📚 Use Cases

* **Students**: Review key points from long lectures in minutes.
* **Teachers**: Create notes or study material from recorded sessions.
* **Researchers**: Summarize interviews, presentations, or conference talks.

---



Let me know if you’d like a version tailored for a specific framework (e.g., Streamlit, Flask) or platform (web, desktop, mobile).





