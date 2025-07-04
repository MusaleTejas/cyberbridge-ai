 🚨 CyberBridge AI

**CyberBridge AI** is an AI-powered platform that bridges cybercrime victims, banks, and cyber police to streamline fraud reporting, triage, and account freezing in real-time. It uses NLP, OTP authentication, and intelligent agent dashboards to speed up the response lifecycle.

---

## 🌐 Live Demo (Optional)
[🔗 View Demo]("https://musaletejas.github.io/cyberbridge-ai/")  
*(Replace with your Dora AI prototype or Vercel link)*

---

## 📌 Features

- 📝 NLP-based complaint extraction (fraud type, urgency, etc.)
- 🤖 AI agents for auto-routing between banks and police
- ❄️ Instant freeze requests for flagged transactions
- 👮 Auto-FIR generation triggers for verified cases
- 📊 Real-time dashboards for victims, banks, and police
- 🔐 JWT + OTP Email verification login
- 📦 Modular microservice architecture

---

## 🛠️ Tech Stack

| Layer         | Technology                     |
|---------------|---------------------------------|
| Frontend      | React.js, TailwindCSS           |
| Backend       | Node.js, Express.js             |
| Database      | MongoDB + Mongoose              |
| NLP Engine    | Python (Flask + spaCy)          |
| Auth          | JWT + OTP via Nodemailer        |
| Hosting       | Vercel (Frontend), Render (Backend)

---

## 🗃️ Folder Structure

```

cyberbridge-ai/
├── client/         # React frontend
├── server/         # Express backend
├── nlp-service/    # Python NLP microservice

````

---

## 🚀 Getting Started

### 📦 Prerequisites
- Node.js & npm
- Python 3.8+
- MongoDB Atlas or Local MongoDB
- Email service for OTP (e.g. SendGrid, Mailgun)

### 🔧 Setup Instructions

```bash
# Clone the repo
git clone https://github.com/MusaleTejas/cyberbridge-ai.git
cd cyberbridge-ai

# Setup Backend
cd server
npm install

# Setup Frontend
cd ../client
npm install

# Setup NLP Service
cd ../nlp-service
pip install -r requirements.txt
python app.py
````

> ⚠️ **Don't forget to add your `.env` variables** in the `server/` and `nlp-service/` folders.

---

## ✉️ .env Sample

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
EMAIL_API_KEY=your_email_api_key
OTP_SENDER=email@example.com
```

---

## 👥 Author

* **Tejas Musale**
  🔗 [GitHub](https://github.com/MusaleTejas)
  📫 [tejasmusale.ds@gmail.com](mailto:tejasmusale.ds@gmail.com)

---

## 🚀 Future Scope

* 🌐 Multilingual support (Hindi, Marathi, etc.)
* 📱 Mobile app with push notifications
* 📊 Fraud heatmap analytics for RBI/MeitY
* 💼 SaaS dashboard for banks and police departments

---

## 📄 License

MIT License — use, modify, and contribute with credit 🙏

---

## 📌 Repo

[🔗 GitHub Repository](https://github.com/MusaleTejas/cyberbridge-ai.git)

