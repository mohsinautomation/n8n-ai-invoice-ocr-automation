# n8n AI Invoice & Receipt OCR Automation

An end-to-end automated workflow built with **n8n**, **Gemini Vision OCR**, **Google Sheets**, and **Telegram API** to extract structured data from incoming email invoices, route exceptions, and maintain real-time audit logs.

## 🚀 Key Features
* 📥 **Gmail Trigger:** Ingests email attachments automatically.
* 🛡️ **File & Data Validation:** Ensures correct file types and validates parsed data completeness.
* 🤖 **AI-Powered OCR:** Uses Gemini Vision API to extract line items, totals, dates, and vendor information.
* 🔀 **Smart Routing:** Handles exceptions cleanly by flagging for human review or logging processing errors.
* 📊 **Automated Logging:** Saves structured data to Google Sheets and sends real-time Telegram alerts.

## 🛠️ Tech Stack
* **Workflow Engine:** n8n
* **AI / OCR:** Gemini Vision API
* **Integrations:** Google Sheets, Telegram Bot API, Gmail

## 📄 License
This project is licensed under the [MIT License](LICENSE).
