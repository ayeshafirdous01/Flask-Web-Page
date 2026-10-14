# Task 2: Introduction to Python and Flask

A beginner-friendly Flask web application that demonstrates how to create a local web server and handle different URLs with routes.

## Features
- Home page at `/`
- About page at `/about`
- Shared CSS styling
- Navigation links between pages
- Responsive layout

## Technologies
- Python
- Flask
- HTML
- CSS

## Setup and Run

1. Install Python 3.
2. Open a terminal in this project folder.
3. (Recommended) Create and activate a virtual environment:

   **Windows**
   ```bash
   py -m venv .venv
   .venv\Scripts\activate
   ```

   **macOS/Linux**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

5. Start the Flask development server:
   ```bash
   python app.py
   ```

6. Open the local URL shown in the terminal (usually http://127.0.0.1:5000).

Visit:
- `http://127.0.0.1:5000/` — Home page
- `http://127.0.0.1:5000/about` — About page

## Project Structure

```text
task-2-python-flask/
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
├── templates/
│   ├── index.html
│   └── about.html
└── static/
    └── style.css
```

## Learning Outcomes
- Basic Flask application setup
- URL routing with `@app.route()`
- Rendering HTML templates
- Serving static CSS files
- Running a local development server

**Note:** `debug=True` is enabled for local learning only. Do not use Flask's debug server in production.
