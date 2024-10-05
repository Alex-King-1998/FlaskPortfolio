# Flask Portfolio

This is a Flask-based portfolio website showcasing projects and skills. The website is deployed on Heroku and demonstrates the use of Flask as a backend framework and HTML, CSS for the front end.

## Features

- Homepage with an introduction and links to various sections
- Project showcase section with descriptions of each project
- Contact form with Flask-WTF for validation
- Logos for Flask + Django frameworks, HTML, CSS and JS
- Deployed on Heroku

## Technologies Used

- **Flask** - Python web framework
- **HTML/CSS** - For structuring and styling the front end
- **Heroku** - Cloud platform for deploying the application
- **Gunicorn/Waitress** - WSGI HTTP servers used in production

## Getting Started

To get a local copy of this project up and running, follow these steps.

### Prerequisites

- Python 3.7 or higher
- `pip` for managing Python packages

### Installation

1. **Clone the repository:**
   in terminal:
   git clone https://github.com/Alex-King-1998/FlaskPortfolio.git
   cd FlaskPortfolio

2. **Create a virtual environment:**
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

3. **Install dependencies:**
pip install -r requirements.txt

Run the application:
flask run
The site should now be running on http://127.0.0.1:5000/.
