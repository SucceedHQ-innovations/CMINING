[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Python](https://img.shields.io/badge/Python-3.11-blue.svg)](https://python.org)

# CMINING

**Cryptocurrency mining management platform.**

A full-stack platform for managing and monitoring cryptocurrency mining operations. Includes an admin dashboard, backend API server, desktop application (Electron), and a WebRTC-based mining engine.

## Components

| Component | Stack | Description |
|-----------|-------|-------------|
| `admin-dashboard/` | TypeScript, React, Vite | Web-based admin interface for monitoring mining operations |
| `backend/` | Python (FastAPI/Flask) | REST API for managing miners, wallets, and payouts |
| `electron-app/` | Electron, HTML, JS | Cross-platform desktop client for real-time monitoring |
| `engine/` | Python | Core mining engine for hash rate management and worker coordination |

## Features

- Real-time mining dashboard with live hash rate charts
- Worker management and assignment
- Wallet integration and payout tracking
- Cross-platform desktop client (Windows, macOS, Linux)
- REST API for third-party integrations

## Getting Started

### Backend

```bash
cd backend
pip install -r requirements.txt
python app.py
```

### Admin Dashboard

```bash
cd admin-dashboard
npm install
npm run dev
```

### Desktop App

```bash
cd electron-app
npm install
npm run start
```

## Tech Stack

- **Backend:** Python (FastAPI/Flask)
- **Frontend:** React, TypeScript, Vite
- **Desktop:** Electron
- **Engine:** Python with async workers
- **Database:** PostgreSQL

## License

MIT
