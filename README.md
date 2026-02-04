# 🐺 Wolf Customer Oracle

AI-powered customer support intelligence system for analyzing Help Scout tickets stored in GitHub.

## 🌟 Features

### 📊 Dashboard View
- **All Active Tickets** - View all active tickets across all companies
- Real-time filtering (excludes unassigned & system-generated tickets)
- Click any ticket to get AI-powered troubleshooting guide
- Automatic refresh capability

### 🔍 Company Deep Dive
- **Smart Search** - Search and select from all archived companies
- **Comprehensive Analysis** including:
  - Executive summary
  - Ticket type distribution
  - Sentiment analysis
  - Common issues & patterns
  - Risk factors & strengths
  - Team performance metrics
  - Customer satisfaction scores
  - Key stakeholders
  - Recent activity history

### 🤖 AI-Powered Features
1. **Troubleshooting Guide Generator**
   - 3-step diagnostic & resolution process
   - Tailored to specific customer issues
   - Technical checklists included

2. **Draft Reply Generator**
   - Professional, context-aware responses
   - Copy-to-clipboard functionality
   - References specific conversation details

3. **Pattern Recognition**
   - Identifies recurring issues
   - Suggests proactive improvements
   - Highlights risk factors

## 🚀 Live Demo

**Access the app:** [https://lj-cmyk.github.io/wolf-oracle/](https://lj-cmyk.github.io/wolf-oracle/)

## 🔒 Setup & Security

### What You Need:
1. **GitHub Personal Access Token** with `repo` permissions
2. **Access** to the `lj-cmyk/helpscout-deep-archive` repository

### Security Notes:
- Your GitHub token is **stored only in your browser session**
- Never transmitted anywhere except GitHub's API
- No server-side storage or logging
- All processing happens in your browser

### Creating a GitHub Token:
1. Go to GitHub Settings → Developer settings → Personal access tokens → Tokens (classic)
2. Click "Generate new token (classic)"
3. Give it a name (e.g., "Wolf Oracle Access")
4. Select scope: `repo` (Full control of private repositories)
5. Click "Generate token"
6. **Copy the token** (you won't see it again!)

## 📂 Repository Structure

Your Help Scout archive should be organized as:
