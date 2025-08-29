# Fruit List App

Eine kleine Full-Stack-Anwendung, die FastAPI im Backend mit einem React-Frontend verbindet.  
Das Projekt ermöglicht es, Früchte in eine Liste einzutragen und diese an das Backend zu senden.

## Features

- React-Frontend für die Eingabe von Früchten
- FastAPI-Backend zum Speichern und Abrufen der Früchte
- In-Memory-Speicherung (keine Datenbank erforderlich)
- CORS-Konfiguration für lokale Entwicklung

## Tech-Stack

- **Frontend:** React
- **Backend:** FastAPI, Python
- **Kommunikation:** HTTP (REST API)

  
## Installation

### Backend

1. Virtuelle Umgebung erstellen und aktivieren:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # macOS/Linux
   venv\Scripts\activate     # Windows

2. pip install fastapi uvicorn pydantic
3. python3 main.py
4. cd frontend
5. npm install
6. nmp run dev
