# 🔥 Burn
*An AI-powered mindfulness, journaling & habit-tracking assistant — the opposite of burnout.*

![Azure](https://img.shields.io/badge/Azure-Cloud-blue?logo=microsoftazure)
![Hackathon](https://img.shields.io/badge/Hackathon-2026-green)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

---

## 🌟 Overview
**Problem:** People struggle with consistency, motivation, and self-awareness when building healthier habits and practicing mindfulness. Existing tools are fragmented and rarely adapt to emotional states.  

**Solution:** *Burn In* integrates mindfulness, journaling, and habit tracking into one AI companion. It adapts to user mood, provides supportive prompts, and surfaces insights to help users thrive instead of burn out.

---

## ✨ Features
- 🧘 **Mindfulness Support**: Guided breathing and grounding exercises, adaptive to stress level.  
- 📓 **Journaling & Reflection**: Contextual prompts, free-form journaling, sentiment analysis, and insights.  
- ✅ **Habit Tracking**: Define habits, track streaks, receive gentle encouragement.  
- 📊 **Insights Dashboard**: Visualize mood trends, habit consistency, and journaling themes.  

---

## 🏗️ Architecture
![Architecture Diagram](docs/architecture.png)

**Tech Stack**
- **Frontend:** React (or your chosen framework)  
- **Backend:** Azure Functions + Microsoft Agent Framework  
- **Database:** Azure Cosmos DB  
- **Search & Insights:** Azure AI Search  
- **AI Services:** Azure Cognitive Services (Text Analytics, Speech)  
- **Hosting:** Azure App Service  

---

## 🚀 Setup Instructions

### Prerequisites
- Azure account (Free Trial available)  
- Node.js or Python  
- Git installed  

### Steps
```bash
# Clone the repository
git clone https://github.com/yourusername/burn-in.git
cd burn-in

# Install dependencies
npm install
# or
pip install -r requirements.txt

# Run locally
npm start
# or
python app.py

# Deploy to Azure
az webapp up --name burn-in-app --resource-group burn-in-rg
