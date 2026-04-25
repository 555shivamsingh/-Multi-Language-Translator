# -Multi-Language-Translator
🌍 Multi-Language Translator + 🔊 Voice (M2M100)

A powerful AI-based Multi-Language Translator built using Meta’s M2M100 model with an interactive Gradio UI and Text-to-Speech (TTS) support.

This project can translate text between multiple languages without relying on English as an intermediate language, and also allows users to listen to the translated output.

🚀 Features
🌐 Translate between multiple languages (100+)
🤖 Powered by M2M100 (Facebook AI model)
🔍 Auto handling of source & target languages
🎛️ Interactive UI using Gradio
🔊 Text-to-Speech (TTS) using gTTS
⚡ Real-time translation
☁️ Public shareable web app (via Gradio)
🛠️ Tech Stack
Python
Transformers (Hugging Face)
SentencePiece
Gradio
gTTS (Google Text-to-Speech)
📦 Installation

Clone the repository:

git clone https://github.com/your-username/multilang-translator-m2m100.git
cd multilang-translator-m2m100

Install dependencies:

pip install transformers sentencepiece gradio gTTS
▶️ Usage

Run the application:

python app.py
🧠 How It Works
Uses M2M100 model for direct multilingual translation
Tokenizer encodes input text with source language
Model generates translated output in target language
gTTS converts translated text into speech
🎮 Demo Interface
Enter text
Select source & target language
Click Translate
Click 🔊 Speak to listen
🌍 Supported Languages (Sample)
English (en)
Hindi (hi)
French (fr)
German (de)
Spanish (es)
Chinese (zh)
Japanese (ja)
Korean (ko)
📂 Project Structure
multilang-translator-m2m100/
│── app.py
│── README.md
📸 Output Example
Input: Hello Shivam  
Source: en  
Target: hi  

Output: नमस्ते शिवम
🔊 Voice Feature
Converts translated text into audio
Supports limited languages via gTTS
Fallback to English if language not supported
⚠️ Limitations
gTTS supports limited languages for audio
Model size (~1.2GB) may require good RAM
Slower on CPU (recommended: GPU)
🚀 Deployment

You can deploy this app easily on:

Hugging Face Spaces
Google Colab (temporary link)
Local machine

For permanent hosting:

gradio deploy
📌 Future Improvements
🎤 Speech-to-Text input
📱 Mobile-friendly UI
⚡ Faster model (distilled version)
🌐 Language auto-detection
🧠 Add translation history
