# 🤖 AI Customer Feedback Automation

An AI-powered workflow built with **n8n** that automatically analyzes customer feedback and updates the results in Google Sheets.

## 📌 Overview

This project demonstrates how AI can be integrated into everyday business workflows without building a complete application.

Whenever a customer submits a Google Form, the response is added to Google Sheets and triggers an n8n workflow. An AI Agent then analyzes the feedback and generates structured insights.

## 🔄 Workflow

Google Form  
↓  
Google Sheets  
↓  
n8n Google Sheets Trigger  
↓  
AI Agent  
↓  
Category + Sentiment + Summary + Suggested Response  
↓  
Update Google Sheets

## ✨ Features

- **Automatic trigger** when a new feedback response is submitted
- **AI categorization** of customer feedback
- **Sentiment analysis** — Positive, Neutral, or Negative
- **Automatic summarization**
- **AI-generated customer response**
- **Structured AI output**
- **Automatic update of the original Google Sheets row**

## 🛠️ Technologies

- **n8n** — workflow automation
- **Google Forms** — feedback collection
- **Google Sheets** — data storage and output
- **AI Agent / LLM** — feedback analysis
- **Structured Output Parser** — structured AI responses

## 🧪 Testing

The workflow was tested with multiple real Google Form submissions covering different scenarios, including:

- Delivery-related feedback
- Website experience
- Positive and negative customer feedback

The AI successfully processed the submissions and returned the expected category, sentiment, summary, and suggested response.

## 🎯 Key Learning

This project demonstrates how AI can be connected to real-world events and business workflows using low-code automation. It provided practical experience with **triggers, AI agents, data mapping, structured outputs, and automated actions**.

## 📂 Workflow

The main workflow consists of:

1. **Google Sheets Trigger** — detects new responses.
2. **AI Agent** — analyzes the feedback.
3. **Structured Output Parser** — organizes the AI response.
4. **Update Row** — writes the AI results back to Google Sheets.
