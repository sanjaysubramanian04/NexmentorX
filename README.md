# 🎯 NexMentorX – Career Development Platform

NexMentorX is a full-stack web application designed to help users **analyze their skills, identify gaps, and generate personalized career roadmaps**.  
The system combines **rule-based analysis with real-time insights using LLM integration**.

> ⚠️ Source code is kept private due to future product development and commercialization.

---

# 🏗️ Tech Stack

### Frontend
- HTML5  
- CSS3  
- JavaScript

### Backend
- Node.js  
- Express.js  

### Database & Authentication
- Firebase Authentication  
- Firebase Firestore  

### AI Integration
- Gemini LLM API (for real-time roadmap generation)

### Deployment
- Vercel (Hosting)  

---

# 🔄 Complete System Workflow

## 1️⃣ User Input
- User enters:
  - Skills  
  - Interests  
  - Career goals  
- Input validation handled using JavaScript  

---

## 2️⃣ Frontend Processing
- Built using HTML, CSS, and JavaScript  
- Handles user interaction and form submission  
- Sends API requests using `fetch`  
- Updates UI dynamically based on response  

---

## 3️⃣ API Communication
- Frontend sends a `POST` request:

- Data is transferred in JSON format  

---

## 4️⃣ Backend Processing (Node.js + Express)

### 🔹 Skill Analysis Engine
- Processes user input  
- Categorizes skills into domains  
- Identifies missing or weak areas  

---

### 🔹 Rule-Based Filtering
- Matches user skills with suitable career paths  
- Filters relevant roles  
- Generates initial structured roadmap  

---

## 5️⃣ Gemini LLM Integration (Real-Time Analysis)

- Processed data is sent to Gemini API  
- Generates:
  - Personalized career roadmap  
  - Recommended technologies  
  - Step-by-step learning path  
  - Industry insights  

---

## 6️⃣ Database Handling (Firebase)
- Stores:
  - User profiles  
  - Skill analysis results  
  - Generated roadmaps  
- Firebase Authentication manages secure login and signup  

---

## 7️⃣ Response Generation
- Backend returns:
  - Skill gap analysis  
  - Career recommendations  
  - Structured roadmap  

---

## 8️⃣ Frontend Display
- Displays:
  - Dashboard view  
  - Skill analysis results  
  - Roadmap timeline  
- Dynamic UI updates using JavaScript  

---

# 🖼️ UI Preview

<p align="center">
  <img src="https://github.com/sanjaysubramanian04/NexmentorX/blob/47140c708a55addbd9992c379c828f5b3008f038/next1.png" width="700"/>
  <img src="https://github.com/sanjaysubramanian04/NexmentorX/blob/d2e161f313cc9256b2410cb3d49c1c95d5c61ee1/next2.png" width="700"/>
  <img src="https://github.com/sanjaysubramanian04/NexmentorX/blob/3065a47cef6a505bc0853ae7eedf81e4f3b0745f/next3.png" width="700"/>
  <img src="https://github.com/sanjaysubramanian04/NexmentorX/blob/2233c2257fd8640ba1cb58c131a7c4f203d82741/next4.png" width="700"/>
  <img src="https://github.com/sanjaysubramanian04/NexmentorX/blob/bb5d8ef092a91dfb5d0457a2ae1faf0499ec84fe/next5.png" width="700"/>
</p>

---

# 🔒 Project Note
This repository contains **only workflow and UI previews**.  
Source code is private for future commercial use.

---

# 🎯 Key Highlights
- Full-stack web application  
- Skill-gap analysis system  
- Real-time roadmap generation using LLM  
- Clean and scalable architecture  

---

# 🚀 Future Enhancements
- Advanced analytics dashboard  
- Resume-based skill extraction  
- Integration with job platforms  
- Mobile application version  
- Personalized learning tracking
