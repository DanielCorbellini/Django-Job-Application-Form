# Job Application Form - Django Web App

## Overview

This Django web application provides a simple job application form for users to fill out and submit.
The form collects information such as first name, last name, email, available start date, and current occupation and
stores it in a database file (db.sqlite3).
After submission, success messages are displayed to the user, and an email is sent.

## Prerequisites

Before running this Django application, ensure that you have the following prerequisites installed:

- Python (3.x recommended)
- Django

## Email Configuration

This Django application uses email functionality.
Below are the email configuration settings that you can find in the settings.py file:

``` python 
EMAIL_BACKEND = "django.core.mail.backends.smtp.EmailBackend
EMAIL_HOST = "smtp.gmail.com"
EMAIL_PORT = 587
EMAIL_USE_TLS = True
EMAIL_HOST_USER = "THE SENDER EMAIL ADDRESS"
EMAIL_HOST_PASSWORD = "THE APP PASSWORD TO SEND THE EMAIL CORRECTLY"
```

- <b>Email Host User:</b> Replace <b>"THE SENDER EMAIL ADDRESS"</b> with the actual email address you want to
  use as the sender.
  This is the email address from which your application will send emails.

- <b>Email Host Password:</b> To send emails securely, you should generate an "App Password" from your email provider
  (in this case, Gmail) and replace <b>"THE APP PASSWORD TO SEND THE EMAIL CORRECTLY"</b> with the generated password.
  This password is used to authenticate your application when sending emails.

- <b>Email Host:</b> The SMTP server's hostname is set to <b>"smtp.gmail.com"</b>. You should replace this with the
  hostname of your
  email service provider if you're not using Gmail.

Please make sure to keep your email credentials secure and avoid storing them directly in your code repository.
Consider using environment variables or a secure configuration management solution to protect sensitive information.

## Incomplete Contact Page

Please note that the contact page in this Django application is currently incomplete. I will finish it soon.