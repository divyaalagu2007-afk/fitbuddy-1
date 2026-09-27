# FitBuddy – AI Fitness Plan Generator

FitBuddy is an AI-powered web application that generates personalized 7-day fitness plans.

## Technologies

- Python
- FastAPI
- Gemini AI
- Jinja2
- SQLAlchemy
- SQLite
- HTML
- CSS
- Uvicorn

## Architecture

Browser
    ↓
FastAPI
    ↓
Gemini AI
    ↓
SQLAlchemy
    ↓
SQLite

Jinja2 is used to render the frontend pages.

## Features

### 1. User Registration

The user enters:

- Name
- User ID
- Age
- Weight
- Fitness goal
- Workout intensity

### 2. AI Workout Generation

Gemini generates a 7-day workout plan.

### 3. Nutrition Tip

Gemini generates a concise nutrition/recovery tip.

### 4. Feedback

The user can submit feedback.

Gemini creates an updated plan.

### 5. Database

User and plan information is stored in SQLite.

### 6. Admin Dashboard

Administrators can view users and their plans.

### 7. Delete User

Administrators can delete users.

## Installation

Create virtual environment:

```powershell
python -m venv .venv