# 🚀 Vyapar Setu (Bharat Biz Agent)

**AI-Powered Business Assistant for India's 60M+ SMBs**

Vyapar Setu is a practical, scalable solution designed to empower local shopkeepers (Kirana stores) by bringing enterprise-level tools to their fingertips through a simple **Telegram Bot** and a powerful **Web Dashboard**.

It bridges the gap between traditional business operations and modern digital management using an AI agent that understands natural language (Hinglish).

---

## 📌 Problem Statement

Small and medium businesses (SMBs) in India struggle with:

- Managing orders and invoices efficiently  
- Tracking inventory in real time  
- Handling customer credit (udhaar)  
- Using tools that feel too complex or disconnected from daily workflows  

Most shop owners already operate through conversational platforms like WhatsApp or Telegram, but existing solutions don’t integrate naturally into this behavior.

**Vyapar Setu** solves this by allowing shop owners to simply type or speak commands in Hindi/Hinglish while the system handles execution and backend management.

---

## 🌟 Key Features

### 🗣️ Hinglish AI Bot
Understands natural language commands like:
- *"Raju ka 500 ka bill bana do"*  
- *"Stock check karo"*

### 🧾 Instant Invoicing
- Generates PDF invoices instantly  
- Allows seamless sharing with customers  

### 📦 Smart Inventory
- Auto-updates stock after each order  
- Sends low-stock alerts  

### 💳 Udhaar (Credit) Tracking
- Tracks pending payments  
- Maintains customer-wise credit records  

### 📊 Interactive Dashboard
- Clean and responsive UI  
- Visualize:
  - Sales
  - Inventory
  - Order history  

---

## 🛠️ Tech Stack

| Layer        | Technology |
|-------------|-----------|
| Backend     | Python, FastAPI |
| Database    | SQLite (zero-config) |
| Bot         | Telegram Bot API (`python-telegram-bot`) |
| Frontend    | HTML5, TailwindCSS, Vanilla JS (SPA) |
| PDF Engine  | ReportLab |
| Deployment  | Docker |

---

## 🐳 Quick Start (Docker - Recommended)

### 1. Configure Environment
Create a `.env` file:
```env
TELEGRAM_BOT_TOKEN=your_token_here


## 📂 Project Structure

vyapar-setu/
│
├── app.py              # FastAPI backend + dashboard
├── telegram_bot.py     # Bot logic & NLP handling
├── database.py         # SQLite setup & queries
├── invoices/           # Generated PDFs
├── bharat_biz.db       # Local database
├── docs/               # Documentation
└── start.sh            # Helper script

---

## 💡 Roadmap

- WhatsApp integration (Meta API)  
- OCR for handwritten bill recognition  
- Multi-language support (Tamil, Telugu, Bengali, etc.)  
- GST calculation and filing features  
- Voice command support  

---

## 🤝 Contribution

Contributions, ideas, and feedback are welcome.  
Feel free to open issues or submit pull requests.

---

## 📬 Contact

- GitHub: https://github.com/aspartic-gthb  
- Email: (add your personal + institute email here)

---

**Built to simplify business for Bharat.**
