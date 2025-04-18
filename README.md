# News Radio App

An application that fetches news, summarizes it, and reads it live on internet radio.

## Features
- Fetch news from top news APIs
- Summarize articles using NLP
- Convert text to speech
- Broadcast audio over internet radio

## Setup Instructions

### Backend
1. Navigate to the `backend/` directory.
2. Install dependencies using:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the backend server:
   ```bash
   python app.py
   ```

### Frontend
1. Navigate to the `frontend/` directory.
2. Install dependencies using:
   ```bash
   npm install
   ```
3. Start the React app:
   ```bash
   npm start
   ```

### Broadcasting
Configure `broadcaster.py` with the correct stream URL for your internet radio service (e.g., Icecast/Shoutcast).
