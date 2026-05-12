# Interview Tracking and Candidate Management System

A Django-based web application for managing candidate information, interview rounds, feedback, and hiring pipeline status.

## Overview

This project helps recruiters or HR teams organize candidate records during the hiring process. It supports candidate profile creation, interview status updates, feedback tracking, and a dashboard view for monitoring hiring progress.

## Features

- Add and manage candidate details
- Track candidate progress across interview stages
- Update statuses such as Applied, Screening, Technical, HR, Offered, Hired, and Rejected
- Store interview feedback with round name, interviewer, rating, and comments
- View dashboard metrics for active, hired, rejected, and total candidates
- Supports SQLite for local development and MySQL for production-style setup

## Tech Stack

- Python
- Django
- HTML
- CSS
- JavaScript
- MySQL
- SQLite

## Project Structure

```text
interview-tracking-system/
  manage.py
  requirements.txt
  schema.sql
  candidates/
  interview_tracker/
  templates/
  static/
```

## Run Locally

```powershell
cd "C:\Users\Srinu\Documents\New project\interview-tracking-system"
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver 5001
```

Open:

```text
http://127.0.0.1:5001
```

## MySQL Setup

Set these environment variables before running migrations:

```powershell
$env:DB_HOST="localhost"
$env:DB_USER="root"
$env:DB_PASSWORD="your_password"
$env:DB_NAME="interview_tracker"
python manage.py migrate
python manage.py runserver 5001
```

## Resume Summary

Built a Django-based interview tracking and candidate management system to manage candidate details, interview rounds, status updates, feedback, and hiring pipeline analytics.
