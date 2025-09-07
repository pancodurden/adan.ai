# adan.ai
adan.ai 🚀

Adan.AI is a futuristic local AI assistant that works fully offline, protects user privacy, and integrates multiple features into one system.

⸻

✨ Features
	•	💬 Local chat with DeepSeek R1 (7B)
	•	📂 Extract text from PDF, Word, Excel, HTML
	•	📝 Summarize long documents
	•	🎭 Sentiment & emotion analysis
	•	🔊 Natural speech with ElevenLabs TTS
	•	🖥 Futuristic Apple-inspired UI

⸻

🛠 Built With
	•	Backend: Python, FastAPI
	•	Frontend: HTML, CSS, JavaScript
	•	AI Core: DeepSeek R1 (7B), GPT-OSS generated code
	•	TTS: ElevenLabs API
	•	Text Parsing: pdfminer.six, python-docx, python-pptx, openpyxl, BeautifulSoup4
    ⚡ Quickstart
    # Clone repo
git clone https://github.com/pancodurden/adan.ai.git
cd adan.ai

# Create environment
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

# Copy example env
cp .env.example .env
# Add your API keys inside .env

# Run backend
uvicorn backend:app --reload --port 8899

 Team
	•	Ali Suat Batmaz – Backend Architect
	•	Timur Meriç Uslupehlivan – Frontend Architect
	•	Ahmet Arda – Research & Testing
	•	Sevilay Batmaz – Legal/Parental Representation