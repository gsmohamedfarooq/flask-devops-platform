# Flask DevOps Platform

A simple Python Flask application used to demonstrate an end-to-end DevOps lifecycle.

## Endpoints

- GET `/` - Application welcome message
- GET `/health` - Application health check
- GET `/info` - Application information

## Local setup

```bash
python -m venv .venv
source .venv/Scripts/activate
pip install -r requirements.txt
python app.py
