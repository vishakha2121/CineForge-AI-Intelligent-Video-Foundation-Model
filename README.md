# 🎬 CineForge AI
### *Intelligent Video Foundation Model*

[![Python Version](https://img.shields.io/badge/python-3.9+-blue.svg)](https://python.org)
[![React Version](https://img.shields.io/badge/react-18.0+-61dafb.svg)](https://reactjs.org)
[![FastAPI](https://img.shields.io/badge/fastapi-0.68+-009688.svg)](https://fastapi.tiangolo.com)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

> Transform your ideas into videos using natural language. Generate, edit, summarize, caption, and search videos - all through simple conversations.

---

## 📋 Table of Contents
- [Overview](#-overview)
- [Key Features](#-key-features)
- [Technology Stack](#-technology-stack)
- [Architecture](#-architecture)
- [Installation Guide](#-installation-guide)
- [Quick Start](#-quick-start)
- [API Documentation](#-api-documentation)
- [Project Structure](#-project-structure)
- [Usage Examples](#-usage-examples)
- [Configuration](#-configuration)
- [Development Guide](#-development-guide)
- [Deployment](#-deployment)
- [Testing](#-testing)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🎯 Overview

**CineForge AI** is an intelligent video foundation model that bridges human creativity with artificial intelligence. It empowers users to:

- 🎨 **Generate** videos from text descriptions
- ✂️ **Edit** videos using natural language commands
- 📝 **Summarize** long videos into highlights
- 🏷️ **Caption** videos with automatic transcription
- 🔍 **Search** videos using semantic understanding

All through an intuitive, beautiful interface - no technical expertise required!

---

## ✨ Key Features

### 🎨 Text-to-Video Generation
```python
# Example: Generate a video
prompt = "A serene sunset over mountains with birds flying"
video = cineforge.generate_video(prompt, duration=10, style="cinematic")

# Navigate to backend
cd backend

# Create virtual environment
python -m venv venv

# Activate virtual environment
# Windows:
venv\Scripts\activate
# Linux/Mac:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Copy environment variables
cp .env.example .env

# Edit .env with your configurations
nano .env

# Start PostgreSQL
sudo service postgresql start

# Create database
sudo -u postgres psql
CREATE DATABASE cineforge_db;
CREATE USER cineforge_user WITH PASSWORD 'your_password';
GRANT ALL PRIVILEGES ON DATABASE cineforge_db TO cineforge_user;
\q

# Run migrations
alembic upgrade head

# Navigate to frontend
cd ../frontend

# Install dependencies
npm install

# Copy environment variables
cp .env.example .env

# Edit .env with your configurations
nano .env