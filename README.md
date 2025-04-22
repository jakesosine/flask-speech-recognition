# Flask Template App

A simple Flask application with multiple HTML templates.

## Setup

1. Create and activate a virtual environment:
```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```
pip install -r requirements.txt
```

3. Run the application:
```
python app.py
```

4. Open a browser and navigate to `http://127.0.0.1:5000/`

## Project Structure

- `app.py` - Main Flask application with routes
- `templates/` - Directory containing HTML templates
  - `index.html` - Home page template
  - `about.html` - About page template
  - `contact.html` - Contact page template
  - `interview.html` - Interview page with speech recording and transcription
- `requirements.txt` - Python dependencies

## Features

- Speech recording and transcription on the interview page
- Audio recording download capability
- Real-time speech-to-text display 