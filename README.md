# 🌍 Multi-Language Translator
🔊 AI Translator with Voice Output (M2M100)

A powerful AI-based translator built using Meta’s M2M100 model.
This application translates text between multiple languages and converts the output into speech.

🚀 Features
Translate between 100+ languages
Direct translation (no English dependency)
Interactive UI using Gradio
Text-to-Speech (TTS) support
Real-time translation
🛠️ Tech Stack
Python
Transformers (Hugging Face)
SentencePiece
Gradio
gTTS
📦 Installation
git clone https://github.com/your-username/multilang-translator-m2m100.git
cd multilang-translator-m2m100
pip install transformers sentencepiece gradio gTTS
▶️ Usage
python app.py
🎮 Demo Workflow
Enter text
Select source language
Select target language
Click Translate
Click Speak to hear output
📸 Example

Input: Hello Shivam
Source: en
Target: hi

Output: नमस्ते शिवम

📂 Project Structure
multilang-translator-m2m100/
│── app.py
│── README.md
│── Multi_Language_Translator.ipynb
⚠️ Limitations
Large model size (~1GB+)
Slower on CPU
Limited TTS language support
🚀 Deployment

You can deploy using:

Hugging Face Spaces
Google Colab
Local system
📌 Future Improvements
Speech-to-Text input
Mobile-friendly UI
Faster lightweight model
Language auto-detection
