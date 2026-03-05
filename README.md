# Research Questionnaire Portal

A secure, browser-based participant management system for research data collection. This tool generates cryptographically secure anonymous codes for survey participants and tracks their progress across multiple questionnaire rounds.

![Portal Preview](https://img.shields.io/badge/Portal-Research%20Tool-purple?style=for-the-badge)
![Privacy First](https://img.shields.io/badge/Privacy-Local%20Storage-success?style=for-the-badge)

## 🌟 Features

- **Secure Code Generation**: Cryptographically random 8-digit participant identifiers (QS-XXXXXXXX format)
- **Dual Survey Support**: Easy access to Round 1 (2025 Data) and Round 2 (Most Recent) questionnaires
- **Privacy Protection**: 
  - No personal data collection
  - Local browser storage (no server required)
  - "Shared Device" mode for public computers (session-only storage)
- **Participation Tracking**: Visual log of survey access times
- **Responsive Design**: Works on mobile, tablet, and desktop
- **Modern UI**: Glassmorphism design with smooth animations

## 🚀 How to Use

1. **Generate Code**: Click "Generate Code" to create your unique participant ID
2. **Copy**: Click "Copy Code" to save it to your clipboard
3. **Complete Surveys**: 
   - Click "Round 1 Questionnaire" and paste your code
   - Return and click "Round 2 Questionnaire" using the **same code**
4. **Shared Device?**: Check "I'm using a shared device" if on a public computer (clears data when tab closes)

## 🔒 Privacy & Security

- All data stored locally in your browser (localStorage/sessionStorage)
- No backend server or database
- No cookies or tracking scripts
- No personal identifiers collected
- Code persists only on your device (unless shared mode enabled)

## 🛠️ Tech Stack

- **Frontend**: Pure HTML5, CSS3, Vanilla JavaScript
- **Styling**: CSS Variables, Glassmorphism effects, CSS Grid/Flexbox
- **Storage**: Web Storage API (localStorage/sessionStorage)
- **Security**: Web Crypto API for random code generation

## 📦 Deployment

This is a static website that can be hosted on any static hosting service:
- GitHub Pages (recommended)
- Netlify
- Vercel
- Any web server

## 👨‍💻 Creator

**Muhammad Daniya**
- Email: mudaniya13@gmail.com
- Role: Research Portal Developer

---

*Note: This tool is designed for research purposes to maintain participant anonymity while ensuring data can be matched across survey rounds.*
