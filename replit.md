# Jovian Careers

## Overview
A Flask-based job listings website for Jovian Careers. Displays open positions and company information.

## Project Structure
- `app.py` - Main Flask application with job data and routes
- `templates/home.html` - Homepage template using Bootstrap 5

## Running the Application
The app runs on port 5000:
```bash
python app.py
```

## Dependencies
- Flask (Python web framework)
- Bootstrap 5 (CSS framework, loaded via CDN)

## Recent Changes
- Fixed JOBS data structure (changed from set to list)
- Fixed syntax errors (missing commas, double comma)
- Configured to run on 0.0.0.0:5000 for Replit
