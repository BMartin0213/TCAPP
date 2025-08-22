# T&C Scanner App

**Author:** Brandon Martin  
**Copyright:** © 2025 Brandon Martin, All rights reserved.

---

## Overview

T&C Scanner is a React + Capacitor mobile app with an Express backend that scans Terms & Conditions of websites for potential **privacy, IP, and unethical clauses**.  
It uses **OpenAI GPT** for AI-powered analysis and displays issues with **risk severity levels**.

---

## Features

- Scan any company’s T&C via URL
- AI highlights potential red flags with Low/Medium/High severity
- Google homepage-style interface
- Mobile-ready via Capacitor
- Live backend deployable on Render, Heroku, or Vercel
- Ready for Google Play and App Store

---

## Folder Structure

- `client/` → React frontend
- `server/` → Node/Express backend
- `nginx/` → NGINX reverse proxy configuration
- `docker-compose.yml` → Docker setup for local development
- `capacitor.config.json` → Capacitor mobile wrapper configuration

---

## Installation (Development)

1. Clone the repo:
```bash
git clone https://github.com/YOUR_USERNAME/tcscanner.git
cd tcscanner
