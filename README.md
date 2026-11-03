# 🌦️ Daily Weather Newsletter – n8n Workflow

An automated weather newsletter built with **n8n** that retrieves daily weather data from the Open-Meteo API, processes the information, and generates a clear, user-friendly weather update delivered directly to your inbox.

This project demonstrates how workflow automation and API integrations can simplify everyday tasks and deliver useful information automatically.

## 🚀 Workflow Overview

The workflow automates the following steps:

1. **Schedule Trigger:** Starts the workflow automatically at a scheduled time.
2. **HTTP Request:** Fetches weather data from the Open-Meteo API.
3. **Data Processing:** Extracts and organizes relevant weather information.
4. **AI Processing:** Generates a readable and structured weather summary.
5. **Email Delivery:** Sends the daily weather newsletter to the recipient.

## 🛠️ Technologies & Tools

- n8n – Workflow automation.
- Open-Meteo API – Weather data retrieval.
- HTTP Request – API integration.
- AI / LLM – Weather summary generation.
- Gmail – Email delivery.

## 📋 Prerequisites

Before running this workflow, you need:

- An n8n instance (cloud or self-hosted).
- An email account connected through n8n credentials.
- An API connection to Open-Meteo.
- An AI provider/API connection if required by the workflow.

## ⚙️ How to Use

1. Download the workflow JSON file from this repository.
2. Open your n8n instance.
3. Select **Import from File**.
4. Import the downloaded JSON file.
5. Configure your credentials and required settings.
6. Adjust the location and schedule if needed.
7. Execute the workflow and test the email output.

## 📂 Repository Contents

- `daily-weather-newsletter.json` – Exported n8n workflow.

## 💡 What You'll Learn

- Working with APIs in n8n.
- Using HTTP Request nodes.
- Processing structured JSON data.
- Integrating AI into automated workflows.
- Sending automated emails.

## 🎓 Workshop Project

This workflow was demonstrated as part of the free workshop:

**AI Automation Engineering using n8n**

Presented by **Eng. Tasnim Alshair**.

---

Built for learning, experimentation, and practical automation. ✨
