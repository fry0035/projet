# Mon Premier Projet IA

Simple API de classification de texte avec Flask.

## Installation

```bash
pip install -r requirements.txt
```

## Lancement

```bash
python app.py
```

## Test

```bash
curl -X POST http://localhost:5000/predict -H "Content-Type: application/json" -d '{"text":"Ce film est génial!"}'
```
