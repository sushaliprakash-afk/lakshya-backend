# 🛠️ Lakshya Backend – Azure-Powered Civic-Tech APIs

This repository contains the serverless backend logic for **Lakshya**, India’s gamified civic engagement platform. Built with Azure Functions and designed for scale, the backend handles pledge submissions, karma tracking, leaderboard generation, and sponsor notifications — all in real time.

## 🔗 Frontend Repository  
👉 [Lakshya Frontend](https://github.com/sushaliprakash-afk/lakshya)

## 🌐 Live Frontend Demo  
🔗 [Visit Lakshya](https://sushaliprakash-afk.github.io/lakshya)

---

## 🧠 Azure Architecture

| Service              | Purpose                                                  |
|----------------------|----------------------------------------------------------|
| **Azure Functions**  | Stateless API endpoints for frontend integration         |
| **Cosmos DB**        | Stores pledges, karma points, and user metadata          |
| **Logic Apps**       | Automates sponsor notifications and reward triggers      |
| **Notification Hubs**| Sends real-time updates to users                         |
| **Azure AD B2C**     | (Optional) Secures user identity for personalized access |
| **Machine Learning** | (Planned) Analyzes pledge trends and engagement patterns |

---

## 📦 API Endpoints

| Endpoint               | Method | Description                                      |
|------------------------|--------|--------------------------------------------------|
| `/api/submitPledge`    | POST   | Accepts pledge data from frontend form           |
| `/api/metrics`         | GET    | Returns real-time impact stats (karma, users)    |
| `/api/leaderboard`     | GET    | Returns top Karma earners                        |
| `/api/pledges`         | GET    | Returns recent pledges for Community Wall        |
| `/api/notify`          | POST   | Triggers sponsor notification via Logic Apps     |

---

## 📁 Folder Structure
├── api/
│   ├── submitPledge/
│   ├── metrics/
│   ├── leaderboard/
│   ├── pledges/
│   └── notify/
├── shared/
│   └── utils/
├── host.json
├── local.settings.json
└── README.md

🚀 Sponsor-Ready Features
- Real-Time Metrics: Showcase civic impact with live dashboards
- Gamified Engagement: Karma points and leaderboards drive participation
- Automated Outreach: Logic Apps notify sponsors instantly
- Scalable & Secure: Azure-native stack ensures reliability and privacy

