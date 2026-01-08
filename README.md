# Event Management REST API

## Project Overview
This project is a RESTful web API developed using **FastAPI** and **MongoDB Atlas**.  
It manages events, attendees, venues, ticket bookings, and multimedia assets such as event posters, promotional videos, and venue photos.

## Technologies Used
- **Python 3.11**
- **FastAPI** – web framework for building APIs
- **Uvicorn** – ASGI server
- **MongoDB Atlas** – cloud NoSQL database
- **Motor** – asynchronous MongoDB driver
- **Pydantic** – data validation and settings management
- **Python-dotenv** – environment variable management
- **Requests** – HTTP library for Python
- **Git & GitHub** – version control
- **Vercel** – for API deployment

## Environment Setup

### 1. Virtual Environment
A Python virtual environment was created to isolate project dependencies:
```bash
python -m venv .venv
# Activate virtual environment:
# Windows
.venv\Scripts\activate
# Mac/Linux
source .venv/bin/activate
