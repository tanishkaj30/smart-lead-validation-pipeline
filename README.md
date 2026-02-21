# Smart Lead Validation & Enrichment Workflow

## 🚀 Overview
This project is an automation workflow built using n8n that processes new leads automatically.

It validates incoming lead data, checks required fields, cleans data, verifies email validity, enriches lead information, stores valid and invalid leads separately, and sends real-time Slack notifications.

## ✨ Features
- Automated lead capture from Google Sheets
- Required field validation
- Data cleaning and normalization
- Email validation logic
- Lead enrichment simulation
- Separate sheets for valid and invalid leads
- Real-time Slack notifications

## 🛠 Tech Stack
- n8n (workflow automation)
- Google Sheets API
- Slack API
- JavaScript (Code nodes)

## 🔄 Workflow Steps
1. New lead trigger from Google Sheets
2. Check required fields
3. Clean and validate data
4. Email validity check
5. Lead enrichment
6. Store valid leads
7. Store invalid leads
8. Send Slack notification

## 📊 Use Case
Helps teams automate lead qualification and reduce manual effort.

## ▶️ How to Run
1. Import workflow.json into n8n
2. Connect Google Sheets credentials
3. Connect Slack credentials
4. Activate workflow

## 🔮 Future Improvements
- Add duplicate detection
- CRM integration
- Error monitoring
- Retry mechanism

## 💡 Author
Tanishka Joshi
