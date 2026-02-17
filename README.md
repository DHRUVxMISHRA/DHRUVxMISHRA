<!-- <h1 align="center">Dhruv Mishra 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=Android+Developer;Building+Women+Safety+App;Learning+DevOps+%26+Docker;Open+Source+Enthusiast" />
</p>



<hr style="border:1px solid #30363d;">


<p align="center">
  <img src="giphy.gif" width="900"/>
</p>

<hr style="border:1px solid #30363d;">


### 👨‍💻 About Me

- 🎓 B.Tech CSE Student at Arya College of Engineering
- 📱 Currently building: Women Safety App
- 🔥 Learning: Android + Firebase + DevOps
- 🐳 Exploring: Docker, Linux, CI/CD
- 💡 Goal: Build impactful real-world applications

<hr style="border:1px solid #30363d;">


<h2 align="center">🏗 Women Safety App – System Architecture</h2>

<p align="center">
  <img src="https://raw.githubusercontent.com/DHRUVxMISHRA/DHRUVxMISHRA/main/women-safety-architecture.svg" width="1000"/>
</p>

<hr style="border:1px solid #30363d;">

<h2 align="center">🧠 Project Deep Dive – SOS Intelligence Flow</h2>

### 🚨 Emergency Trigger Flow (Current Implementation)

When SOS is triggered via:
- 📳 Shake Detection (Accelerometer)
- 🔘 Double Volume Key Press
- 🆘 Manual SOS Button

The system executes:

1. 📍 Capture Real-Time Location
2. 🔔 Start Foreground Location Service
3. 🌐 Send Location to FastAPI Backend
4. 📩 Backend triggers:
   - Twilio SMS with Live Location
   - WhatsApp Message via Twilio API

---

### 🔄 Planned Enhancements (In Progress)

- 🔁 Continuous Location Streaming to Backend
- 💾 Local Storage + Retry Mechanism if Internet Fails
- 📊 SOS History Logging in Firebase Firestore
- ☁ Future Cloud Deployment (AWS)

---

### 🤖 AI Chatbot Architecture

- Powered by OpenAI API
- Strict Prompt Engineering
- Context-Limited to Safety Topics Only
- Backend Managed Conversation Control
- Integrated into FastAPI Service Layer

The chatbot is designed to:
- Provide emergency guidance
- Offer safety tips
- Assist users during high-risk situations
- Avoid non-safety responses

---

### 🧩 Engineering Decisions

- MVVM + Repository Pattern for Clean Architecture
- Foreground Services for Reliable Tracking
- Sensor-Based Trigger Detection (No UI Required)
- Backend-Controlled SMS & WhatsApp Dispatch
- Scalable Architecture for Future Cloud Deployment

<hr style="border:1px solid #30363d;">

<h2 align="center">⚙️ Engineering Highlights</h2>

- 🔒 Background-Safe Emergency Trigger System
- 📡 Real-Time Location Capture via Foreground Service
- 🧠 Sensor-Level Detection (Accelerometer + Volume Events)
- 🌐 Backend-Controlled Notification Dispatch (Twilio)
- 🗃 MongoDB for Structured Emergency Records
- 🔐 Firebase Authentication Layer
- 🧩 Modular MVVM Architecture
- 🚀 Future-Ready Cloud Deployment Strategy
- 🤖 AI Safety Assistant with Controlled Prompting

<hr style="border:1px solid #30363d;">

<h2 align="center">🔐 Security & Privacy Engineering</h2>

### 🛡 Current Implementation

- 🔒 All backend communication over HTTPS
- 🔑 API keys handled securely on backend (not exposed in Android client)
- 📡 Location data transmitted via secure REST endpoints
- 🔐 Firebase Authentication for user identity management
- 🤖 OpenAI API managed from backend only (no client-side exposure)

---

### 🚧 In Progress / Planned Security Enhancements

- 🔐 Environment-based secret management (.env → cloud secret manager)
- 🗝 Token-based request validation between Android & Backend
- 🚦 Rate limiting on SOS endpoints
- 🧾 Secure logging for emergency events
- 📦 Encrypted storage for local emergency cache
- 🛑 Prompt injection prevention hardening in chatbot
- 🧠 Abuse detection & spam protection

---

### 🧩 Privacy Design Philosophy

- Only necessary data is transmitted
- Location shared only during active SOS
- Backend-controlled emergency dispatch
- Future: Automatic data expiration for old SOS logs

<hr style="border:1px solid #30363d;">

<h2 align="center">👨‍💻 My Engineering Ownership</h2>

### 📱 Android System Owner

I independently designed and developed the complete Android application layer of the Women Safety System.

My responsibilities included:

- 🏗 Full Android architecture implementation (MVVM + Clean Architecture)
- 🚨 Complete SOS trigger system logic
- 📳 Sensor-based emergency detection (Accelerometer + Volume events)
- 📡 Real-Time Location Foreground Service
- 🌐 Retrofit integration with FastAPI backend
- 🔐 Secure API communication handling
- 🧩 Modular repository-based data flow design

---

### 🧠 System-Level Contributions

- Designed Android-to-Backend communication pipeline
- Engineered foreground-safe emergency execution logic
- Built sensor-triggered background-safe emergency activation
- Structured Android project using scalable architecture patterns

---

### 🎯 Engineering Focus

My primary expertise in this project:

Android Systems Engineering  
Backend API Integration  
Real-Time Event Handling  
Clean Architecture Design

<hr style="border:1px solid #30363d;">
### 🛠 Tech Stack

<p>
<img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white"/>
<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white"/>
<img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
</p>

<hr style="border:1px solid #30363d;">

<h2 align="center">📊 GitHub Stats</h2>

<p align="center">
  <img src="https://raw.githubusercontent.com/DHRUVxMISHRA/DHRUVxMISHRA/main/stats.svg"/>
</p>


<p align="center">
  <img src="https://streak-stats.demolab.com?user=DHRUVxMISHRA&theme=tokyonight&hide_border=true&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff" />
</p>

<hr style="border:1px solid #30363d;">

<h3 align="center">🐍 Contribution Snake</h3>

<p align="center">
  <img src="https://raw.githubusercontent.com/DHRUVxMISHRA/DHRUVxMISHRA/snake-output/github-contribution-grid-snake.svg"/>
</p>

<hr style="border:1px solid #30363d;">

<h2 align="center">📊 3D Contribution Graph</h2>

<p align="center">
  <img src="https://raw.githubusercontent.com/DHRUVxMISHRA/DHRUVxMISHRA/gh-pages/profile-night-rainbow.svg"/>
</p>


<!-- <h2 align="center">📊 Contribution Graph</h2> -->

<!-- <p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=DHRUVxMISHRA&theme=github-compact&bg_color=0d1117&color=58a6ff&line=58a6ff&point=ffffff&area=true&hide_border=true" />
</p> -->

<!-- <img src="https://github-readme-activity-graph.vercel.app/graph?username=DHRUVxMISHRA&theme=tokyo-night&area=true&hide_border=true" /> -->


<!--
**DHRUVxMISHRA/DHRUVxMISHRA** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
--> 
<!-- <h1 align="center">Dhruv Mishra 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=26&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=650&lines=Android+%2B+Backend+Engineer;Building+Real-Time+Safety+Systems;MVVM+%7C+FastAPI+%7C+Clean+Architecture;Open+Source+Enthusiast" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Real--Time%20Women%20Safety%20System-Actively%20Developing-58A6FF?style=for-the-badge"/>
</p>

<p align="center">
  <em>I build systems that react before the user has time to panic.</em>
</p> -->
<p align="center">
  <img src="https://raw.githubusercontent.com/DHRUVxMISHRA/DHRUVxMISHRA/main/blue-cyber-hero.svg" width="100%"/>
</p>

<hr style="border:1px solid #30363d;">

<p align="center">
  <img src="giphy.gif" width="900"/>
</p>

<hr style="border:1px solid #30363d;">

## 👨‍💻 About Me

- Android + Backend Systems Engineer  
- Builder of real-time event-driven safety applications  
- Strong focus on Clean Architecture (MVVM)  
- Exploring DevOps, Cloud & scalable backend systems  

---

## 🏗 Real-Time Women Safety System – Architecture

<p align="center">
  <img src="https://raw.githubusercontent.com/DHRUVxMISHRA/DHRUVxMISHRA/main/women-safety-architecture.svg" width="1000"/>
</p>

---


## 🎬 SOS Trigger Execution Overview

This system executes emergency dispatch within seconds using:
- Sensor-based detection
- Foreground-safe tracking
- Backend-triggered messaging

<!--## 🎬 Live SOS Trigger Simulation
<!-- <p align="center">
  <!-- Replace with your demo gif 
  <img src="sos-demo.gif" width="800"/>
</p> 

*(Recording in progress – demonstrating real-time emergency trigger execution)*-->

---

## 🚨 Emergency Execution Pipeline

**Trigger Sources**
- Shake Detection (Accelerometer)
- Double Volume Key Press
- Manual SOS Activation

**Execution Flow**
1. Capture real-time location  
2. Start foreground tracking service  
3. Send coordinates to FastAPI backend  
4. Backend dispatch:
   - Twilio SMS (Live Location)  
   - WhatsApp Alert via Twilio API  

---

## 📈 System Characteristics

- Event-driven emergency architecture  
- Foreground-safe real-time tracking  
- Backend-controlled dispatch logic  
- AI-assisted safety chatbot  
- Modular MVVM Android structure  
- Designed for cloud scalability  

---

## ⚙️ Engineering Execution

### Android Ownership
- Complete MVVM + Clean Architecture implementation  
- Foreground service tracking  
- Sensor-triggered emergency activation  
- Retrofit backend integration  
- Secure client-server communication  

### Backend Integration
- FastAPI REST APIs  
- MongoDB persistence  
- OpenAI safety-restricted chatbot  
- Twilio emergency dispatch system  

---

## 🔐 Security & Privacy Thinking

- HTTPS-only communication  
- Backend-managed API keys  
- Firebase authentication  
- No client-side secret exposure  

**In Progress**
- Token validation layer  
- Rate limiting  
- Secure secret management  
- Offline encrypted emergency cache  

---

## 🟢 Currently Building

- Continuous backend location streaming  
- SOS history logging system  
- Cloud deployment strategy  
- Deployment automation pipeline  

---

## 🛠 Core Tech Stack

<p>
<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white"/>
<img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black"/>
<img src="https://img.shields.io/badge/Twilio-F22F46?style=for-the-badge&logo=twilio&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/>
</p>

---

## 📊 GitHub Activity

<p align="center">
  <img src="https://streak-stats.demolab.com?user=DHRUVxMISHRA&theme=tokyonight&hide_border=true" />
</p>

---

## 🐍 Contribution Activity

<p align="center">
  <img src="https://raw.githubusercontent.com/DHRUVxMISHRA/DHRUVxMISHRA/snake-output/github-contribution-grid-snake.svg"/>
</p>

---

## 🧊 3D Contribution Graph

<p align="center">
  <img src="https://raw.githubusercontent.com/DHRUVxMISHRA/DHRUVxMISHRA/gh-pages/profile-night-rainbow.svg"/>
</p>

