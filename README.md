# AI-Interview-Simulator
A web-based application that replicates real interview scenarios using artificial intelligence. It streamlines candidate evaluation by recommending domain-specific questions, transcribing spoken answers locally, and scoring them against predefined responses.

<h2>🧩 Components</h2>
Frontend: Developed with React.js and Vite.

Backend (Node.js): REST API built with Express.

Backend (Flask): Python server integrating Whisper locally for audio transcription and response evaluation.

<h2>🚀 Getting Started</h2>

1. Open the .env files and fill in the required environment variables according to your application's configuration requirements.

2. Flask Server
```bash
cd Flask
pip install -r requirements.txt
python app.py
```
3. Node Server
```bash
cd node
npm install
node index.js
```
4. React Frontend
```bash
cd client/interviewPro
npm install
npm run dev 
```
<h2>🧠 Features</h2>
Client

* Google OAuth login
* Category-based question display
* Result and report visualization

Node.js Backend

* Auth & session handling
* Queue and audio upload endpoints
* JWT protection

Flask Backend

* Local Whisper-based STT
* Cosine similarity scoring
* Transcription & evaluation APIs

<h2>🛠️ Tech Stack</h2>

Frontend: React.js, Vite, CSS

Backend: Node.js (Express), Python (Flask)

Local ML: Whisper, Cosine similarity, TF-TDF

Other Tools: RabbitMQ, JWT, Google OAuth

<h2>👨‍💻 Team</h2>

* Pranjal Sharma
* Rachit Kumar Choudhary

