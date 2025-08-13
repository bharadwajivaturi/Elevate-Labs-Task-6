# Elevate-Labs-Task-6
Build a Portfolio Website with Flask
# Portfolio Website with Flask

A personal portfolio website built with Flask that includes a functional contact form.

## Features

- Responsive design using Bootstrap 5
- Sections for About, Education, Projects, and Skills
- Contact form with email functionality
- Ngrok integration for easy testing

## Setup Instructions

1. Clone this repository
3. Configure your Gmail credentials in `app.py`:
   - Replace `your_email@gmail.com` with your actual Gmail
   - Replace `your_app_password` with a generated app password
4. Run the application: `python app.py`

## Dependencies

- Flask
- pyngrok
- smtplib (standard library)
- email (standard library)

## Security Notes

- Never commit actual credentials to version control
- Consider using environment variables for sensitive data
- Gmail may require enabling "Less secure app access" or creating an app-specific password
