# HachiNet Full Stack — HACHI NET WARNASARI

Paket ini menyertakan:
- `frontend/src/App.jsx` (antarmuka React + Tailwind + Vite)
- `backend/backend.js` (server Express + API Key + MikroTik RouterOS API + Telnet OLT + database bersama `backend/data/shared-db.json`)
- `backend/.env.example` (template variabel lingkungan)

## Menjalankan Backend
```bash
cd backend
cp .env.example .env
# Edit .env lalu isi API_KEY dan konfigurasi MikroTik/OLT
npm install
npm start
```

## Menjalankan Frontend (React + Vite)
```bash
cd frontend
npm install
npm run dev
```
