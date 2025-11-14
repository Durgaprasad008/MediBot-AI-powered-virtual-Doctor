MediBot — AI-Powered Virtual Doctor

MediBot is an advanced AI-powered medical assistant designed to help users describe symptoms, upload images, and receive AI-generated preliminary analysis.
It uses vision models, LLMs, voice input, and text-to-speech output to simulate an intelligent virtual doctor.

🚀 Features
🩺 1. Symptom Understanding (NLP)

Users can type or speak symptoms

Groq API (LLaMA / Mixtral) used for fast medical reasoning

Generates:

Possible conditions

Causes

First-aid guidance

When to visit a real doctor

👁️ 2. Skin Disease Image Analysis

Uploads supported:

Acne

Skin Rashes

Dandruff

Other visible issues

AI identifies:

Condition

Severity

Suggested care

🎤 3. Voice Support (Optional)

Supports:

Microphone input

AI speech recognition

Text-to-speech (GTTS or ElevenLabs)

🔊 4. AI Doctor Voice Output

Generates audio from the AI diagnosis.

🌐 5. Gradio Web UI

Simple, fast, and beautiful interface.

🧩 Project Structure
MediBot/
│
├── gradio_app.py              # Main app UI
├── brain_of_the_doctor.py     # AI decision-making logic
├── voice_of_the_doctor.py     # TTS module (GTTS/ElevenLabs)
├── voice_of_the_patient.py    # Speech recognition module
│
├── acne.jpg                   # Sample images
├── skin_rash.jpg
├── dandruff-optimized.webp
│
├── requirements.txt
├── README.md
├── .env.example               # Example of environment variables
└── .gitignore

🔧 Installation
1. Clone the repository
git clone https://github.com/YOUR_USERNAME/MediBot.git
cd MediBot

2. Install dependencies
pip install -r requirements.txt

3. Create .env

Copy:

cp .env.example .env


Add your API keys:

GROQ_API_KEY=your_key
ELEVENLABS_API_KEY=your_key   # optional

▶️ Run the App
python gradio_app.py


The app will open in the browser.

🔒 Environment Variables
Variable	Purpose
GROQ_API_KEY	Required for AI medical reasoning
ELEVENLABS_API_KEY	Optional for premium voice output
📝 Disclaimer

MediBot is an educational project, not a substitute for real medical advice.
Always consult a certified healthcare professional.

🤝 Contributing

Pull requests are welcome!
If you want to add features such as:

Firebase authentication

Full medical knowledge base

Advanced diagnosis models

Feel free to open an issue.

⭐ Give a Star!

If this project helps you, please ⭐ the repository — it motivates further development.
