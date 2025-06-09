# 🌱 FarmGPT - AI-Powered Agricultural Assistant

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Deploy on Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/your-username/farmgpt)
[![Twitter Follow](https://img.shields.io/twitter/follow/farmgpt?style=social)](https://twitter.com/farmgpt)

FarmGPT delivers **AI-powered farming advice** via SMS and web, optimized for low-bandwidth rural areas.

## ✨ Features
- 💬 **Chatbot** for crop/pest questions (GPT-3.5 Turbo)
- 📸 **Image-based disease detection** (TensorFlow.js)
- 📡 **Offline-first PWA** with SMS fallback
- 🌦️ **Hyperlocal weather alerts** (OpenWeatherMap API)
- 🌍 **Multilingual support** (50+ languages)

## 🛠️ Tech Stack
| Component       | Technology                  |
|----------------|----------------------------|
| Frontend       | React PWA                  |
| Backend        | Node.js + Express          |
| Database       | Firebase Realtime Database |
| AI             | OpenAI GPT-3.5 + TF.js     |
| SMS Gateway    | Twilio API                 |
| Hosting        | Vercel (Frontend) + Render (Backend) |

## 🚀 Quick Start

### Prerequisites
- Node.js ≥16
- Firebase account
- Twilio account (free trial)

### Installation
```bash
# Clone repository
git clone https://github.com/your-username/farmgpt.git
cd farmgpt

# Install dependencies
cd client && npm install
cd ../server && npm install
