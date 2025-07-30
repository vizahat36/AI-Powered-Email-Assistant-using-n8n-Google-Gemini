
# 🤖 AI-Powered Email Assistant using n8n + Google Gemini

This project demonstrates how to create an AI Agent in [n8n](https://n8n.io) that interprets user chat messages and sends intelligent emails using natural language processing.

---

## 🛠️ Components Used

- **Trigger:** `When Chat Message Received`
- **AI Agent:** Configured with:
  - `Google Gemini Chat Model` (for understanding the message)
  - `Simple Memory` (to remember previous info)
  - `Send email in Send Email` (to send the actual email)

---

## 🧠 AI Agent Instructions

> You are **Email Genie**, a smart and friendly assistant that receives user chat messages and sends emails.
> - Extract recipient email, subject, and body from the message.
> - If something is missing, ask the user for it.
> - Use the "Send email" tool to send the composed message.
> 
> Example:  
> "Send an email to john@example.com about the project meeting tomorrow at 3PM."

---

## 📸 Workflow Diagram

![Workflow Screenshot](./docs/Screenshot (48).png)

---

![Demo](https://your-uploaded-gif-or-video-link.gif)


## 💡 Sample Inputs to Test

1. `Send an email to vijahath@gmail.com with subject "Update" and body "AI agent is now live!"`
2. `Email Raj at raj@example.com and tell him the demo is postponed.`
3. `Send an email to anjali@xyz.com`

---

## 📌 Technologies Used

- **n8n (No-code workflow automation)**
- **Google Gemini (Chat Model)**
- **SMTP (Email sending)**
- **Simple Memory (State retention)**

---

## 🚀 Future Improvements

- Dynamic email templates
- Scheduled email reminders
- Smart reply detection
](https://drive.google.com/file/d/1X6ovRPQ0zWgQejIAU-poZjWYPfHoMkb7/view?usp=sharing)
