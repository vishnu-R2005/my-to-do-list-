# My Flask App

A simple Flask web application with a Bootstrap-based layout and navigation bar.

## Features
- Flask + Jinja2 templating
- Bootstrap 5 responsive navbar
- Template inheritance (`base.html`)
- Home and About pages

## Project Structure
```
my_flask_app/
│
├── app.py
├── templates/
│   ├── base.html
│   ├── home.html
│   └── about.html
├── static/   # (Optional for CSS, JS, images)
└── README.md
```

## Installation & Setup

1. **Clone the repository** (or create your project folder)
   ```bash
   git clone https://github.com/yourusername/my_flask_app.git
   cd my_flask_app
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate   # Mac/Linux
   venv\Scripts\activate      # Windows
   ```

3. **Install dependencies**
   ```bash
   pip install flask
   ```

4. **Run the app**
   ```bash
   python app.py
   ```
   Then open `http://127.0.0.1:5000` in your browser.

## File Descriptions
- `app.py` — Main Flask application file.
- `templates/base.html` — Base template with navbar and footer.
- `templates/home.html` — Home page content.
- `templates/about.html` — About page content.

## Notes
- Bootstrap is included via CDN; no local CSS required.
- You can add more pages by creating new templates and adding routes in `app.py`.

## License
This project is open-source. You can use and modify it freely.
