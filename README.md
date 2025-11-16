# AI-Powered Community Crisis Reporting Mobile App

<div style="display: flex; gap: 10px; justify-content: center; align-items: center;">
  <img src="./assets/banner.png" width="30%" />
  <img src="./assets/landing.png" width="30%" />
  <img src="./assets/landing1.png" width="30%" />
</div>


**AI-Powered Community Crisis App** is a **mobile application** that allows users to report, view, and engage with community crises in real-time.  

- **Frontend:** React Native (TypeScript + CSS)  
- **Backend:** PHP (separate repository)  
- **API Calls:** Fetch API  
- **AI:** OpenAI for personalized suggestions and classification  
- **Database:** MySQL (handled in backend)  

> Note: The backend is maintained in a separate GitHub repository. Make sure to connect the mobile app to the backend API.

---

## Table of Contents

- [Features](#features)
- [Technology Stack](#technology-stack)
- [Screenshots](#screenshots)
- [Installation Guide](#installation-guide)
- [AI Components](#ai-components)
- [Future Enhancements](#future-enhancements)
- [Author](#author)

---

## Features

### User Features
- **Report a Crisis:** Submit incidents with title, description, severity, and location.  
- **AI Suggestions:** For every report, the app provides **real-time AI recommendations** on what actions users can take immediately.  
- **Community Feed:** View all reported crises from other users.  
- **Comment on Reports:** Engage with posts to provide suggestions or ask questions.  
- **Map Visualization:** All reported crises are displayed on a map with severity-based markers. Users and officials can quickly see locations and assess situations.  
- **AI Classification:** Reports are automatically categorized into Infrastructure, Safety, Health, or Utilities using **OpenAI**.  


---

## Technology Stack

![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Fetch API](https://img.shields.io/badge/Fetch_API-000000?style=for-the-badge&logo=javascript&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)

- **Frontend:** React Native + TypeScript + CSS  
- **Backend:** PHP (separate repo)  
- **API Requests:** Fetch API  
- **AI Module:** OpenAI API for classification, suggestions, and sentiment analysis  
- **Database:** MySQL (handled in backend)  

---

## Screenshots


| Login | Report Crisis | AI Suggestions | |
|--------------|---------------|----------------|----------------|
 ![login](./assets/login.png) | ![report](./assets/add.png) | ![suggestions](./assets/ai-feed.png) | 
|Community Feed  | Report View    | Map View | Commenting | 
|----------------|----------------|----------|------------| 
| ![feed](./assets/feed.png) | ![suggestions](./assets/Post.png) | ![map](./assets/crises-map.png) | ![comments](./assets/comment.png) |

---

## Installation Guide (Mobile App)

### 1. Clone the frontend repository
```bash
git clone https://github.com/yourusername/community-crisis-mobile.git
cd community-crisis-mobile
```

### 2. Install dependencies
```bash
npm install
```
### 3. Configure API

Update your backend API URL and OpenAI key in a .env file or config file:

API_URL=https://your-backend-repo-url/api
OPENAI_API_KEY=your_openai_api_key

### 4. Run the app
```bash
npx react-native run-android   # for Android
npx react-native run-ios       # for iOS
```
Make sure your backend server is running and accessible by the mobile app.

---
## AI Components (Powered by OpenAI)

- Real-Time Suggestions: For each crisis report, AI suggests what users can do immediately to mitigate or respond.

- AI Classification: Automatically categorizes reports into Infrastructure, Safety, Health, or Utilities.

- Sentiment Analysis: Optional feature to analyze comments for community sentiment and concern.

---

## Future Enhancements

- Real-time push notifications for new crisis reports

- Mobile offline support

- Multi-language support

- Integration with emergency services for automated alerts

----
# Author

### Nethononda Nyandano
Full-Stack Developer

- GitHub: https://github.com/Nethononda-Nyandano

- Email: nyandanonethononda8@gmail.com

- Location: South Africa

- Portfolio:

----

# About Me

I am a passionate developer focused on building practical solutions for real-world problems.
This project helps communities report, track, and respond to crises efficiently using a mobile interface connected to a backend API, with AI-powered suggestions and classification provided by OpenAI.











