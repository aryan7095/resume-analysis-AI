# 🚀 Review AI – Intelligent Resume Analyzer & Interview Prep System
<p align="center">

<img src="https://img.shields.io/badge/Frontend-React-blue?style=for-the-badge&logo=react" />
<img src="https://img.shields.io/badge/Backend-Node.js-green?style=for-the-badge&logo=node.js" />
<img src="https://img.shields.io/badge/Database-MongoDB-brightgreen?style=for-the-badge&logo=mongodb" />
<img src="https://img.shields.io/badge/AI-Gemini-orange?style=for-the-badge" />

<br/>

<img src="https://img.shields.io/badge/Auth-JWT-black?style=for-the-badge&logo=jsonwebtokens" />
<img src="https://img.shields.io/badge/PDF-Puppeteer-red?style=for-the-badge&logo=puppeteer" />
<img src="https://img.shields.io/badge/API-Express-lightgrey?style=for-the-badge&logo=express" />

</p>

> Turn your resume into a **job-winning machine** with AI-powered insights, skill gap analysis, and interview preparation.


## 🧠 What is Review AI?

**Review AI** is a full-stack AI-powered platform that:

- 📄 Analyzes your **resume (PDF)**
- 🧑‍💻 Matches it with a **job description**
- 🧾 Considers your **self-description**
- 📊 Generates:
  - Resume match score (0–100)
  - Skill gaps
  - Technical questions
  - Behavioral questions
  - Personalized preparation plan
  - Resume PDF generation




## ✨ Features

- 🔐 JWT Authentication (Login/Register/Logout)
- 📄 Resume Upload & Parsing (PDF)
- 🤖 AI-Powered Analysis (Gemini API)
- 📊 Resume Match Scoring
- 📉 Skill Gap Detection
- 🧠 Technical + Behavioral Questions
- 🗺️ Personalized Preparation Plan
- 📑 Resume PDF Generator (Puppeteer)
- 📚 Interview Report History
- ⚡ Clean Modular Architecture

## 🗂️ Project Structure

```bash
├── .vscode/
│   └── settings.json
├── Backend/
│   ├── src/
│   │   ├── config/
│   │   │   └── database.js
│   │   ├── controllers/
│   │   │   ├── auth.controller.js
│   │   │   └── interview.controller.js
│   │   ├── middlewares/
│   │   │   ├── auth.middleware.js
│   │   │   └── file.middleware.js
│   │   ├── models/
│   │   │   ├── blacklist.model.js
│   │   │   ├── interviewReport.model.js
│   │   │   └── user.model.js
│   │   ├── routes/
│   │   │   ├── auth.routes.js
│   │   │   └── interview.routes.js
│   │   ├── services/
│   │   │   └── ai.service.js
│   │   └── app.js
│   ├── .gitignore
│   ├── package-lock.json
│   ├── package.json
│   ├── server.js
│   └── test.js
├── Frontend/
│   ├── public/
│   │   ├── favicon.svg
│   │   └── icons.svg
│   ├── src/
│   │   ├── components/
│   │   │   └── common/
│   │   │       └── Loader.jsx
│   │   ├── features/
│   │   │   ├── auth/
│   │   │   │   ├── components/
│   │   │   │   │   └── Protected.jsx
│   │   │   │   ├── hooks/
│   │   │   │   │   └── useAuth.js
│   │   │   │   ├── pages/
│   │   │   │   │   ├── Login.jsx
│   │   │   │   │   └── Register.jsx
│   │   │   │   ├── services/
│   │   │   │   │   └── auth.api.js
│   │   │   │   ├── auth.context.jsx
│   │   │   │   └── auth.form.scss
│   │   │   └── interview/
│   │   │       ├── components/
│   │   │       │   ├── Footer.jsx
│   │   │       │   ├── Header.jsx
│   │   │       │   ├── Hero.jsx
│   │   │       │   ├── InterviewForm.jsx
│   │   │       │   └── ReportList.jsx
│   │   │       ├── hooks/
│   │   │       │   └── useInterview.js
│   │   │       ├── pages/
│   │   │       │   ├── Home.jsx
│   │   │       │   └── Interview.jsx
│   │   │       ├── services/
│   │   │       │   └── interview.api.js
│   │   │       ├── style/
│   │   │       │   ├── footer.scss
│   │   │       │   ├── form.scss
│   │   │       │   ├── header.scss
│   │   │       │   ├── hero.scss
│   │   │       │   ├── home.scss
│   │   │       │   ├── interview.scss
│   │   │       │   └── reportList.scss
│   │   │       └── interview.context.jsx
│   │   ├── styles/
│   │   │   └── button.scss
│   │   ├── App.jsx
│   │   ├── app.routes.jsx
│   │   ├── main.jsx
│   │   └── style.scss
│   ├── .env.production
│   ├── .gitignore
│   ├── eslint.config.js
│   ├── index.html
│   ├── package-lock.json
│   ├── package.json
│   ├── README.md
│   └── vite.config.js
└── vercel.json

```


## 🛠️Tech Stack
### **🖥️ Frontend**  
- React (Vite)  
- SCSS  
- Context API  
- Custom Hooks  
## **⚙️ Backend**  
- Node.js  
- Express.js  
- MongoDB + Mongoose  
- JWT Authentication  
- Multer (File Upload)  
## **🤖 AI & Processing**  
- Gemini AI (Content Generation)  
- pdf-parse (Resume Parsing)  
- Puppeteer (HTML → PDF)



## 📈 Future Improvements
- 📊 ATS Score Simulation
- 🎯 Role-specific preparation plans
- 🎥 Mock interview (AI voice)
- 🧠 Behavioral feedback analysis
- 📱 Mobile responsive UI upgrade
## 🤝 Contributing

Pull requests are welcome. For major changes, open an issue first.


## ⭐ Support

If you like this project:

👉 Give it a ⭐ on GitHub
👉 Share it with others
👉 Use it to crack your next interview 😉
