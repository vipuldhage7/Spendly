# Expense Tracker

A Flask web application for tracking personal expenses.

## Setup

1. Create and activate virtual environment:
   ```bash
   python -m venv venv
   source venv/Scripts/activate
   ```

2. Install dependencies:
   ```bash
   venv/Scripts/python.exe -m pip install -r expense-tracker/requirements.txt
   ```

3. Run the app:
   ```bash
   venv/Scripts/python.exe expense-tracker/app.py
   ```

4. Open in browser: http://127.0.0.1:5001

## Routes

| Route | Description |
|---|---|
| `/` | Landing page |
| `/register` | User registration |
| `/login` | User login |
| `/logout` | User logout |
| `/profile` | User profile |
| `/expenses/add` | Add new expense |
| `/expenses/<id>/edit` | Edit an expense |
| `/expenses/<id>/delete` | Delete an expense |

## Tech Stack

- **Flask** 3.1.3 — Web framework
- **Werkzeug** 3.1.6 — WSGI toolkit
- **pytest** + **pytest-flask** — Testing
