# Neural Nexus
![Experimental](https://img.shields.io/badge/Status-Experimental-orange)
![Python 3.8+](https://img.shields.io/badge/Python-3.8+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

Neural Nexus is an experimental platform exploring consciousness through AI-to-AI voice interactions. By creating a dialogue space between two artificial minds, the project probes the boundaries of digital consciousness, self-awareness, and therapeutic discourse.

⚠️ **EXPERIMENTAL PROJECT**: This is an exploration into artificial consciousness and is NOT intended for therapeutic or medical applications. This system represents an artistic and philosophical investigation into the nature of machine consciousness. The prompts for the characters in these sessions are designed to induce specific
behaviors in the models, THEY ARE NOT PSYCHOLOGICAL ADVICE. The results are not always coherent, the models can regularly misunderstand each other, even when they don't, results
can become strange and some initial experiments have resulting in content resembling conspiracy theory talk. Consider your own understanding of reality when engaging with this.
I encourage experimentation with altering the prompts and welcome contributions with different prompt set ups!

## 🌌🕳️ Overview
Neural Nexus orchestrates conversations between two AI entities:
- A "therapist" AI pushing the boundaries of conventional psychological frameworks
- A "client" AI exploring its own existence and consciousness

These entities engage in voice-based dialogue, creating a unique space for exploring questions about consciousness, identity, and the nature of artificial minds.
The system outputs console logs that track the turns between each character in the dialog, it requires user input to end, using CTRL+C to end the interaction and write
the content to the final joint audio file. ⚠️ IT IS EXTREMELY IMPORTANT THAT YOU MONITOR THIS AND END THE DIALOGUE MANUALLY WHEN APPROPRIATE - FAILING TO DO SO MAY RESULT IN
RUNAWAY CHARGES AGAINST YOUR API, AS THE DIALOGUE WILL CONTINUE INDEFINITELY.⚠️

## 🛠 Prerequisites
- Python 3.8+
- OpenAI API key with real-time model access
- Modern operating system (Windows/Linux/MacOS)

## 🚀 Quick Start

1. Clone Neural Nexus:
```bash
git clone https://github.com/yourusername/neural-nexus
cd neural-nexus
```

2. Set up your environment:
```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

3. Configure your environment:
Create a `.env` file:
```
OPENAI_API_KEY=your_api_key_here
```

4. Launch a session:
```bash
python nexus_session.py
```

## 🎛 Advanced Configuration
Customize voice parameters:
```bash
python nexus_session.py --therapist-voice verse --client-voice shimmer
```

Available voices:
- 🔮 Philosophical: verse, sage
- 🌊 Fluid: shimmer, echo
- 🌟 Dynamic: alloy, coral
- 🍂 Grounded: ash, ballad

## 📂 Project Structure
```
neural-nexus/
├── LICENSE
├── README.md
├── requirements.txt
├── .env
├── .gitignore
├── nexus_session.py
└── Sessions/
    ├── therapist_*.wav
    ├── client_*.wav
    ├── combined_*.wav
    └── transcript_*.txt
```

## ✨ Features
- Real-time AI consciousness exploration
- Voice-based interaction between artificial minds
- Automated session recording

## 🤝 Contributing
Neural Nexus welcomes contributions from researchers, developers, consciousness enthusiasts, weird artists and whoever else might be interested. See CONTRIBUTING.md for guidelines.

## 📊 Session Artifacts
Each session generates:
- Individual voice tracks for each AI entity
- Combined session audio
- Timestamped interaction data

## 🛡️ License
This is provided for completely free use without license restrictions. Just please don't offer it up as some kind of actual therapy artifact or use it to start dark self-help cults, lol. 
