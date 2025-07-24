# Booking_Ai_Agent
AI-powered meeting scheduler built with n8n and Gemini API that automates the entire process of collecting user details, understanding intent, finding availability, and booking meetings on both the user's and the company's calendars. Designed for seamless, hands-free scheduling through smart automation.

# 🤖 Booking AI Agent (n8n + Gemini)

This project is an intelligent meeting scheduler built using [n8n](https://n8n.io) and Google's **Gemini API**. It automates the end-to-end process of booking meetings — from capturing user input to scheduling across calendars — with no human involvement required.

## ✨ Key Features

- 🔄 **Full Automation Flow**  
  From capturing user details to finalizing meeting slots, the workflow runs completely autonomously.

- 🧠 **Natural Language Understanding (NLU)**  
  Utilizes Gemini API to process and interpret user input conversationally.

- 📅 **Dual Calendar Integration**  
  Books meetings simultaneously on:
  - The **user’s calendar**
  - The **company’s shared calendar**

- 🧾 **Smart Input Handling**  
  Automatically parses names, times, preferences, and meeting types from user queries.

- 📤 **Automated Confirmation**  
  Sends confirmation emails or messages once the meeting is booked.

- 🧩 **Modular Workflow**  
  Easily extendable to include reminders, follow-ups, or CRM integration.

---

## 🛠️ Automation Flow

```mermaid
graph TD
A[User Inputs Details] --> B[Gemini API Analyzes]
B --> C[Finds Suitable Time Slot]
C --> D[Books on User's Calendar]
C --> E[Books on Company Calendar]
D & E --> F[Sends Confirmation]
