README.md: |
  # 📧 AI Communication Assistant  

  AI-powered email assistant built with **FastAPI (backend)** and **React (frontend)**.  
  It can:  
  - ✅ Fetch emails from DB (or Gmail)  
  - ✅ Summarize emails using AI  
  - ✅ Classify emails (priority, sentiment, etc.)  
  - ✅ Draft smart replies automatically  

  ---

  ## 🚀 Features  
  - Beautiful modern UI with React + Tailwind  
  - AI-powered actions (Summarize, Classify, Draft Reply)  
  - FastAPI backend with Swagger API docs  
  - Gmail API integration (optional)  
  - Responsive design  

  ---

  ## 📂 Project Structure  
ai-comm-assistant/
├── backend/ # FastAPI backend
├── frontend/ # React frontend
├── screenshots/ # Project screenshots
├── README.md


---

## 📸 Screenshots  

### 📨 Email List  
<img width="1919" height="936" alt="email-list png" src="https://github.com/user-attachments/assets/8964e105-4742-4750-b49f-b8287f3ea3b3" />


### 🔍 Email Summary  
<img width="1919" height="1079" alt="email-summary png" src="https://github.com/user-attachments/assets/8255a124-8d9a-4128-89c8-3413a765ddd7" />


### 🏷️ Email Classification  
<img width="1918" height="1035" alt="Screenshot 2025-09-06 020743" src="https://github.com/user-attachments/assets/9d2ceefe-d968-4bbb-b68b-3c735e99581d" />


### ✍️ Draft Reply  
<img width="1919" height="1079" alt="draft-reply png" src="https://github.com/user-attachments/assets/48e67525-09bb-4102-9f52-47b65e484e8f" />


---

## ⚡ Installation  

### Backend (FastAPI)  
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload


cd frontend
npm install
npm run dev


📖 API Endpoints

GET /emails → List emails

POST /emails/{email_id}/summarize → Summarize email

POST /emails/{email_id}/classify → Classify email

POST /emails/{email_id}/draft-reply → Generate draft reply

POST /email/fetch-gmail → Fetch Gmail and store


🛠️ Tech Stack

Frontend: React, Vite, TailwindCSS, Lucide Icons

Backend: FastAPI, Python, Gmail API, OpenAI/Gemini (AI models)

Database: SQLite / PostgreSQL (configurable)



