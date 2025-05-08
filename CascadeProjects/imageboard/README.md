# Imageboard Website

A simple imageboard website where users can upload images with optional comments.

## Features
- Upload images with comments
- View all posts in chronological order
- Responsive design using Bootstrap
- File size limit (16MB)
- Secure file handling
- SQLite database for persistence

## Deployment

### Local Development
1. Install Python dependencies:
```bash
pip install -r requirements.txt
```

2. Run the application:
```bash
python app.py
```

3. Open your browser and navigate to `http://localhost:5000`

### Heroku Deployment
1. Create a Heroku account at https://heroku.com
2. Install Heroku CLI
3. Connect to GitHub repository
4. Deploy using Heroku GitHub integration

## Project Structure
- `app.py`: Main Flask application
- `templates/`: HTML templates
- `static/`: Static files (CSS, JS, images)
- `uploads/`: User uploaded images
- `requirements.txt`: Python dependencies
- `Procfile`: Heroku configuration
- `runtime.txt`: Python version specification
