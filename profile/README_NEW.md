# 💬 HappyHODLers
### AI-Powered Cryptocurrency Chatbot for Real-Time Market Insights

<div align="center">

![React](https://img.shields.io/badge/React-18-61dafb?style=for-the-badge&logo=react)
![Vite](https://img.shields.io/badge/Vite-7-646CFF?style=for-the-badge&logo=vite)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=for-the-badge&logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC?style=for-the-badge&logo=tailwind-css)
![Pyth Network](https://img.shields.io/badge/Powered%20by-Pyth%20Network-7C3AED?style=for-the-badge)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![ETH Global](https://img.shields.io/badge/ETH%20Global-Hackathon-orange?logo=ethereum)](https://ethglobal.com)
[![Live Demo](https://img.shields.io/badge/Live-Demo-success?style=for-the-badge&logo=vercel)](https://happyhodlers.vercel.app)

*Making cryptocurrency accessible through conversational AI*

</div>

---

## 🎯 **What is HappyHODLers?**

**TL;DR:** Chat naturally with an AI-powered assistant to check crypto prices, compare assets, set intelligent alerts, and manage your portfolio—all powered by Pyth Network's ultra-fast oracle data with 400ms updates.

### 💡 **Problem We Solve**

| Current Challenge | Our Solution |
|------------------|--------------|
| ❌ Complex crypto dashboards require technical knowledge | ✅ Natural conversation: *"What's the price of Bitcoin?"* |
| ❌ Price data scattered across multiple exchanges | ✅ Unified data from 15+ exchanges via Pyth Network |
| ❌ Manual price monitoring is time-consuming | ✅ Smart alerts: *"Alert me when ETH reaches $4,000"* |
| ❌ Delayed price feeds lead to missed opportunities | ✅ Real-time updates every 400ms with confidence intervals |

---

## 🌟 **Key Features**

### 🔮 **Pyth Network Integration**
- **Ultra-Fast Updates**: Real-time price feeds with 400ms refresh cycles
- **High Confidence Data**: Aggregated from 15+ premium exchanges
- **15 Supported Assets**: BTC, ETH, SOL, USDC, USDT, DAI, AVAX, MATIC, ARB, OP, BNB, ADA, DOT, LINK, UNI
- **Confidence Intervals**: Know the reliability of every price point

### 🔔 **Intelligent Price Alerts**
- **Natural Language Setup**: *"Alert me when BTC reaches $100k"*
- **Bilingual Support**: Configure alerts in English or Spanish
- **5-Second Monitoring**: Active alerts checked every 5 seconds
- **Smart Notifications**: Instant browser alerts when price targets hit

### 🤖 **AI-Powered Query Detection**
- **Pattern Recognition**: Understands price queries in multiple formats
- **Multi-Language**: Supports English and Spanish naturally
- **Context Awareness**: Interprets "Bitcoin", "BTC", "btc" all correctly
- **Smart Comparisons**: *"Compare ETH and SOL prices"*

### 🎨 **Professional UI/UX**
- **Official Crypto Icons**: Integration with CryptoLogos.cc
- **Responsive Design**: Horizontal PriceCards, comparison views
- **Real-Time Updates**: Live price changes without page refresh
- **Dark Mode Ready**: Modern, accessible interface

### 🔐 **Web3 Wallet Integration**
- **Non-Custodial**: You control your keys, we never touch your funds
- **RainbowKit + Wagmi**: Industry-standard wallet connection
- **Multi-Wallet Support**: MetaMask, WalletConnect, Coinbase Wallet, and more
- **Secure by Design**: All data encrypted, no private key exposure

---

## 🚀 **Quick Start**

### Prerequisites
```bash
Node.js >= 18.0.0
npm >= 9.0.0
Git
```

### Installation (3 Steps)

**1️⃣ Clone & Install**
```bash
git clone https://github.com/HappyHODLers/happyhodlers.git
cd happyhodlers
npm install
```

**2️⃣ Run the Development Server**
```bash
npm run dev
```

**3️⃣ Connect Your Wallet**
- Click "Connect Wallet" button
- Select your preferred wallet (MetaMask, WalletConnect, etc.)
- Approve the connection
- Start chatting!

---

## 💬 **Usage Examples**

### 🗣️ **Chat Interactions**

#### **Example 1: Check a Price**
```
👤 User:
"What's the price of Bitcoin?"

🤖 HappyHODLers:
💰 Bitcoin (BTC)
Price: $67,542.80
24h Change: +3.42%
Confidence: ±$12.50
Last Update: 400ms ago
```

#### **Example 2: Compare Assets**
```
👤 User:
"Compare ETH and SOL"

🤖 HappyHODLers:
📊 Price Comparison:

Ethereum (ETH): $3,245.67
Solana (SOL): $98.32

ETH is 33x more expensive than SOL
ETH 24h: +2.1% | SOL 24h: +5.8%
```

#### **Example 3: Set an Alert (English)**
```
👤 User:
"Alert me when BTC reaches $100,000"

🤖 HappyHODLers:
✅ Price Alert Created!

Asset: Bitcoin (BTC)
Target: $100,000
Current: $67,542.80
Direction: Upward (+$32,457.20 to go)
Status: Active (checking every 5 seconds)

I'll notify you when BTC hits your target! 🔔
```

#### **Example 4: Set an Alert (Spanish)**
```
👤 Usuario:
"Avisame cuando ETH llegue a 4000"

🤖 HappyHODLers:
✅ ¡Alerta de Precio Creada!

Activo: Ethereum (ETH)
Objetivo: $4,000
Actual: $3,245.67
Dirección: Subida (+$754.33 para llegar)
Estado: Activa (verificando cada 5 segundos)

¡Te avisaré cuando ETH alcance tu objetivo! 🔔
```

---

## 🪙 **Supported Assets**

| Category | Assets | Count |
|----------|--------|-------|
| **Major Cryptocurrencies** | BTC, ETH, SOL, BNB, ADA, DOT | 6 |
| **Stablecoins** | USDC, USDT, DAI | 3 |
| **Layer 2 Tokens** | ARB, OP, MATIC | 3 |
| **DeFi Tokens** | AVAX, LINK, UNI | 3 |

**Total Supported: 15 Assets**

All prices are provided by **Pyth Network** oracle with:
- 📡 15+ exchange aggregation
- ⚡ 400ms update frequency
- 🎯 Confidence interval tracking
- 🔒 Cryptographically secured data

---

## 🏗️ **Technical Architecture**

```
┌─────────────────────────────────────────────────────────────────┐
│                   HAPPYHODLERS ARCHITECTURE                      │
└─────────────────────────────────────────────────────────────────┘

┌──────────────────┐      ┌──────────────────┐      ┌─────────────────┐
│   Frontend UI    │      │   Backend API    │      │  Pyth Network   │
│   React + Vite   │◄────►│   Flask Server   │◄────►│  Hermes API     │
│                  │      │                  │      │                 │
│ • Chat Interface │      │ • NLP Processing │      │ • 15+ Assets    │
│ • Price Cards    │      │ • Price Alerts   │      │ • 400ms Updates │
│ • Alert Manager  │      │ • Alert Monitor  │      │ • 15+ Exchanges │
│ • Wallet Connect │      │ • Database CRUD  │      │ • Confidence    │
└──────────────────┘      └──────────────────┘      └─────────────────┘
         │                         │                         
         │                         │                         
         └─────────────────────────┼─────────────────────────┘
                                   │
                                   ▼
                    ┌──────────────────────────┐
                    │   Data Layer             │
                    │   PostgreSQL             │
                    │                          │
                    │ • User Alerts            │
                    │ • Price History          │
                    │ • Chat Logs              │
                    └──────────────────────────┘
```

### 📊 **Data Flow**

1. **User Input** → Natural language query via chat
2. **AI Processing** → Pattern detection for price queries
3. **Pyth Query** → Real-time price fetch from Hermes API
4. **Response Generation** → Formatted price card with confidence
5. **Alert Monitoring** → Background check every 5 seconds
6. **Notification** → Browser alert when target price reached

---

## 🎯 **Price Alert System**

### How It Works

**Setup Phase:**
```javascript
// User types: "Alert me when BTC reaches $100k"
const alert = {
  asset: "BTC",
  targetPrice: 100000,
  currentPrice: 67542.80,
  direction: "upward",
  active: true
}
```

**Monitoring Phase:**
```javascript
// Backend checks every 5 seconds
setInterval(() => {
  const currentPrice = fetchPythPrice("BTC");
  if (currentPrice >= alert.targetPrice) {
    sendNotification("🚨 BTC has reached $100,000!");
    deactivateAlert(alert.id);
  }
}, 5000);
```

**Notification Phase:**
```javascript
// Browser notification appears
new Notification("🎉 Price Alert!", {
  body: "Bitcoin (BTC) reached $100,000!",
  icon: "/crypto-icons/btc.png"
});
```

### Supported Alert Formats

**English:**
- "Alert me when BTC reaches $100,000"
- "Notify me when ETH hits 4000"
- "Tell me when SOL gets to $150"

**Spanish:**
- "Avisame cuando BTC llegue a 100000"
- "Notificame cuando ETH alcance 4000"
- "Dimelo cuando SOL llegue a 150"

---

## 🛠️ **API Endpoints**

### Backend Services (Render.com)
**Base URL:** `https://clary-backend-ai.onrender.com`

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/chat` | POST | Process natural language queries |
| `/create-alert` | POST | Create a new price alert |
| `/get-alerts` | GET | Retrieve all active alerts |
| `/delete-alert` | DELETE | Remove an alert by ID |
| `/price/:symbol` | GET | Get current price for an asset |

### Pyth Network Integration
**Hermes API:** `https://hermes.pyth.network`

```javascript
// Example: Fetch BTC price
const response = await fetch(
  'https://hermes.pyth.network/v2/updates/price/latest?ids[]=0xe62df6c8b4a85fe1a67db44dc12de5db330f7ac66b72dc658afedf0f4a415b43'
);
const data = await response.json();
const btcPrice = data.parsed[0].price.price / 1e8;
```

---

## 📁 **Project Structure**

```
happyhodlers/
│
├── 📁 frontend/                 # React Frontend
│   ├── src/
│   │   ├── components/
│   │   │   ├── Chat.tsx        # Main chat interface
│   │   │   ├── PriceCard.tsx   # Price display component
│   │   │   ├── AlertManager.tsx# Alert configuration
│   │   │   └── WalletConnect.tsx# Web3 wallet integration
│   │   ├── hooks/
│   │   │   ├── usePyth.ts      # Pyth price fetching
│   │   │   └── useAlerts.ts    # Alert management
│   │   ├── utils/
│   │   │   ├── priceFormatter.ts# Currency formatting
│   │   │   └── detectQuery.ts  # NLP pattern matching
│   │   └── App.tsx
│   ├── package.json
│   └── vite.config.ts
│
├── 📁 backend/                  # Flask API
│   ├── app.py                  # Main server
│   ├── routes/
│   │   ├── chat.py             # Chat endpoints
│   │   └── alerts.py           # Alert endpoints
│   ├── services/
│   │   ├── pyth_service.py     # Pyth integration
│   │   ├── nlp_service.py      # Query processing
│   │   └── alert_monitor.py    # Background alert checker
│   ├── models/
│   │   └── database.py         # PostgreSQL models
│   ├── requirements.txt
│   └── render.yaml             # Deployment config
│
├── 📁 contracts/               # Smart Contracts (Future)
│   └── HappyHODLers.sol
│
├── 📁 docs/
│   ├── API.md                  # API documentation
│   └── CONTRIBUTING.md
│
└── README.md
```

---

## 🗺️ **Development Roadmap**

### ✅ **Phase 1: MVP (Completed)**
- [x] Pyth Network integration with 15 assets
- [x] Natural language chat interface
- [x] Price alert system (English + Spanish)
- [x] Real-time price updates (400ms)
- [x] Wallet connection with RainbowKit
- [x] Responsive UI with Tailwind CSS

### 🚧 **Phase 2: Enhanced Features (In Progress)**
- [ ] Portfolio tracking and management
- [ ] Historical price charts
- [ ] Price trend analysis
- [ ] Multi-user support with authentication
- [ ] Mobile app (React Native)
- [ ] Push notifications (Firebase)

### 🔮 **Phase 3: Advanced Features (Planned)**
- [ ] AI-powered price predictions
- [ ] Social trading features
- [ ] Integration with DEX aggregators
- [ ] NFT price tracking
- [ ] DeFi yield opportunities
- [ ] Advanced technical indicators

### 🌟 **Phase 4: Ecosystem Expansion**
- [ ] API for third-party developers
- [ ] Widget for embedding in other apps
- [ ] Browser extension
- [ ] Telegram/Discord bots
- [ ] HappyHODLers governance token

---

## 🧪 **Testing**

### Manual Test Cases

#### **Test 1: Price Query**
```
Input: "What's the price of ETH?"
Expected: Price card showing current ETH price with confidence
Status: ✅ Pass
```

#### **Test 2: Asset Comparison**
```
Input: "Compare BTC and ETH"
Expected: Side-by-side price cards with comparison
Status: ✅ Pass
```

#### **Test 3: Price Alert Creation**
```
Input: "Alert me when SOL reaches $150"
Expected: Confirmation message + active alert in database
Status: ✅ Pass
```

#### **Test 4: Alert Triggering**
```
Setup: Create alert for BTC at $70,000
Action: Wait for price to reach target
Expected: Browser notification appears
Status: ✅ Pass
```

#### **Test 5: Wallet Connection**
```
Action: Click "Connect Wallet" → Select MetaMask
Expected: Wallet address displayed + balance shown
Status: ✅ Pass
```

### Automated Tests

```bash
# Backend unit tests
cd backend
pytest tests/ -v

# Frontend component tests
cd frontend
npm run test

# E2E tests with Cypress
npm run test:e2e
```

---

## 🤝 **Contributing**

We welcome contributions from the community! Here's how you can help:

### **Ways to Contribute**
1. 🐛 **Report Bugs**: Open an issue with details
2. 💡 **Suggest Features**: Share your ideas in discussions
3. 📝 **Improve Docs**: Fix typos or add examples
4. 🔧 **Submit PRs**: Follow our coding standards
5. 🌍 **Translations**: Help us support more languages

### **Development Setup**
```bash
# 1. Fork the repository
# 2. Clone your fork
git clone https://github.com/YOUR_USERNAME/happyhodlers.git

# 3. Create a feature branch
git checkout -b feature/amazing-feature

# 4. Make your changes
# 5. Test thoroughly
npm run test

# 6. Commit with descriptive message
git commit -m "Add amazing feature for price alerts"

# 7. Push to your fork
git push origin feature/amazing-feature

# 8. Open a Pull Request
```

### **Code Style Guidelines**
- **TypeScript**: Follow Airbnb style guide
- **React**: Use functional components with hooks
- **Python**: Follow PEP 8 standards
- **Commits**: Use conventional commits (feat:, fix:, docs:)

---

## 📄 **License**

This project is licensed under the **MIT License**.

```
MIT License

Copyright (c) 2025 HappyHODLers Team

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.
```

See [LICENSE](LICENSE) file for full details.

---

## 🏆 **Hackathon Information**

### **Event Details**
- **Hackathon**: ETH Global 2025
- **Track**: DeFi + Oracle Integration
- **Sponsor**: Pyth Network
- **Theme**: Making crypto accessible through conversational AI
- **Duration**: 48 hours
- **Team Size**: 4 developers

### **Bounty Targets**
- 🎯 **Pyth Network**: Best use of real-time price feeds
- 🎯 **Innovation**: Most user-friendly DeFi application
- 🎯 **Impact**: Solution with highest potential adoption

### **Why HappyHODLers Deserves to Win**

#### ✅ **Pyth Network Integration Excellence**
- ✅ Real-time data from 15+ exchanges via Hermes API
- ✅ 400ms update cycles for lightning-fast prices
- ✅ Confidence intervals displayed to users
- ✅ 15 cryptocurrency price feeds integrated
- ✅ Production-ready implementation

#### ✅ **Innovation & User Experience**
- ✅ First conversational AI for crypto prices powered by Pyth
- ✅ Bilingual support (English + Spanish)
- ✅ Zero learning curve - just chat naturally
- ✅ Smart alert system with natural language
- ✅ Non-custodial, privacy-first design

#### ✅ **Technical Excellence**
- ✅ Modern tech stack (React 18, Vite 7, TypeScript)
- ✅ Web3 integration (RainbowKit, Wagmi, Ethers.js)
- ✅ Production deployment (Vercel + Render.com)
- ✅ Scalable architecture with PostgreSQL
- ✅ Real-time monitoring with 5-second intervals

#### ✅ **Market Potential**
- ✅ Targets 1B+ smartphone users new to crypto
- ✅ Eliminates technical barriers to entry
- ✅ Built for accessibility and inclusion
- ✅ Clear monetization path (premium features)
- ✅ Foundation for broader DeFi ecosystem

---

## 👥 **Team**

<div align="center">

| Role | Responsibilities | Skills |
|------|-----------------|--------|
| 🧠 **AI/Backend Developer** | NLP processing, Pyth integration, Alert system | Python, Flask, PostgreSQL, Pyth SDK |
| 🎨 **Frontend Developer** | UI/UX, React components, Wallet integration | React, TypeScript, Tailwind, Web3 |
| ⛓️ **Blockchain Developer** | Smart contracts, Web3 integration | Solidity, Ethers.js, Wagmi |
| 📊 **Product Manager** | Strategy, Testing, Documentation | Product design, UX research |

</div>

### **Contact the Team**
- 📧 Email: team@happyhodlers.app
- 🐦 Twitter: [@HappyHODLers](https://twitter.com/happyhodlers)
- 💬 Discord: [Join our community](https://discord.gg/happyhodlers)

---

## 🙏 **Acknowledgments**

### **Special Thanks To:**
- 💜 **Pyth Network**: For providing the most reliable oracle data in DeFi
- 🌍 **ETH Global**: For organizing this incredible hackathon
- 🛠️ **Open Source Community**: React, Vite, Tailwind, and all the amazing tools we used
- 🎨 **CryptoLogos.cc**: For professional cryptocurrency icons
- 🧪 **Beta Testers**: Everyone who tested and provided feedback

### **Powered By:**
- [Pyth Network](https://pyth.network) - Real-time oracle data
- [Hermes API](https://hermes.pyth.network) - Price feed aggregation
- [RainbowKit](https://rainbowkit.com) - Wallet connection
- [Wagmi](https://wagmi.sh) - React hooks for Ethereum
- [Render.com](https://render.com) - Backend hosting
- [Vercel](https://vercel.com) - Frontend deployment

---

## 🔗 **Important Links**

<div align="center">

| Resource | Link |
|----------|------|
| 🌐 **Live Demo** | [happyhodlers.vercel.app](https://happyhodlers.vercel.app) |
| 📚 **Documentation** | [docs.happyhodlers.app](https://docs.happyhodlers.app) |
| 🐙 **GitHub Repo** | [github.com/HappyHODLers](https://github.com/happyhodlers) |
| 📹 **Demo Video** | [youtube.com/watch?v=demo](https://youtube.com/watch) |
| 📊 **Pitch Deck** | [pitch.happyhodlers.app](https://pitch.happyhodlers.app) |
| 🔮 **Pyth Network** | [pyth.network](https://pyth.network) |
| 📖 **Pyth Docs** | [docs.pyth.network](https://docs.pyth.network) |

</div>

---

## 🛠️ **Troubleshooting**

### Common Issues

**Issue 1: Wallet won't connect**
```
Solution:
1. Ensure MetaMask is installed
2. Check you're on a supported network
3. Refresh the page
4. Clear browser cache
```

**Issue 2: Prices not updating**
```
Solution:
1. Check internet connection
2. Verify backend is running (backend health check)
3. Check browser console for errors
4. Try refreshing the page
```

**Issue 3: Alerts not triggering**
```
Solution:
1. Ensure browser notifications are enabled
2. Keep the tab open (background monitoring requires active tab)
3. Check alert is still active in database
4. Verify target price is reasonable
```

**Issue 4: Backend server timeout**
```
Solution:
1. Backend on Render.com may sleep after inactivity
2. First request wakes it up (~30 seconds)
3. Wait for server to respond
4. Subsequent requests will be fast
```

### Need Help?

- 📧 **Email Support**: support@happyhodlers.app
- 💬 **Discord**: Ask in #support channel
- 🐛 **Bug Reports**: Open a GitHub issue
- 📖 **Documentation**: Check docs.happyhodlers.app

---

<div align="center">

## 🎉 **Thank You for Checking Out HappyHODLers!**

### 🌟 **Making Cryptocurrency Accessible, One Conversation at a Time**

![Built with Pyth](https://img.shields.io/badge/Built%20with-Pyth%20Network-7C3AED?style=for-the-badge)
![ETH Global](https://img.shields.io/badge/ETH%20Global-Hackathon%202025-FF6B35?style=for-the-badge)

---

**"Chat naturally. Invest smartly. HODL happily."**

---

*© 2025 HappyHODLers. Built with ❤️ during ETH Global Hackathon.*

### ⭐ **If you like this project, give us a star!**

[![GitHub Stars](https://img.shields.io/github/stars/HappyHODLers/happyhodlers?style=social)](https://github.com/HappyHODLers/happyhodlers)

</div>
