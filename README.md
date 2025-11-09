# Personal Portfolio (Flask)

This is a minimal personal portfolio demo built with Flask and Jinja2. It includes a simple contact form that flashes a confirmation message (no email is sent).

Requirements
- Python 3.8+
- Virtual environment (recommended)

Quick start (Windows PowerShell)

```powershell
python -m venv .venv; .\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
python .\app.py
# Then open http://127.0.0.1:5000 in your browser
```

Notes
- For production, set a secure `SECRET_KEY` and don't run with `debug=True`.
- The contact form currently only flashes a message; integrate an email provider or database as needed.
