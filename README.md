# IoT-DePIN-OSINT-scanner

An open-source real-time scanner for IoT devices and decentralized infrastructure nodes (DePIN), combining active fingerprinting and OSINT analysis.

## 🛠 Tech Stack
- FastAPI (Python)
- React + Tailwind CSS
- WebSockets (real-time)
- SQLite (for local storage)

## 🚀 Features
- LAN & IoT Discovery (SNMP, UPnP, mDNS)
- DePIN Node Scanner (e.g., Helium, Pollen)
- Risk Scoring System
- Real-time Monitoring Dashboard
- Free OSINT Source Integration

## 🧪 Local Setup

### Backend (FastAPI)
```bash
cd backend
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload

### Frontend (React + Tailwind)
cd frontend
npm install
npm run dev
