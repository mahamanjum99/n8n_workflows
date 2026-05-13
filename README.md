# ⚙️ n8n Automation Workflows Collection

This repository contains a collection of **automation workflows built using n8n**.  
These workflows demonstrate real-world use cases like API integration, scheduling tasks, email automation, database handling, and data logging.

---

## 📌 About n8n

n8n is a powerful **workflow automation tool** that allows you to connect APIs, services, and databases visually without heavy coding.

---

## 📁 Workflows Included

### 1. 📧 Email Automation Workflow
- Sends automated emails using SMTP
- Triggered via **Webhook or schedule**
- Useful for notifications and alerts

---

### 2. 🌦️ Weather Data Logger
- Fetches live weather data using OpenWeather API
- Extracts city, temperature, and weather description
- Stores data into Google Sheets
- Runs automatically on schedule

---

### 3. 👤 User Engagement Email System
- Fetches inactive users from MySQL database
- Sends reminder emails to users who haven’t logged in
- Updates user status after notification
- Includes conditional logic (IF node)

---

### 4. 🌐 Webhook + Google Sheets Automation
- Receives form data via webhook
- Sends automated email confirmation
- Logs data into Google Sheets
- Fully automated data pipeline

---

### 5. ⏰ Scheduled API Workflow
- Runs at specific intervals
- Calls external APIs
- Processes and stores response data

---

## 🧩 Tech Stack

- n8n (Workflow Automation)
- MySQL (Database)
- Google Sheets API
- SMTP Email Service
- OpenWeather API
- HTTP Requests

---

## 🚀 How to Use

1. Clone this repository:
```bash
git clone https://github.com/your-username/n8n-workflows.git

2.Open n8n dashboard
3.Import workflow JSON:
4.Click Import Workflow
5.Select .json file from repo
6.Configure credentials:
Email SMTP
Google Sheets API
MySQL connection
API keys
7.Activate workflow and run
