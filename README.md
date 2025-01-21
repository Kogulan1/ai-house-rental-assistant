## **🏡 AI House Rental Assistant**
🚀 **AI-powered house rental assistant that automates property search, applications, and document management in the Swiss rental market.**  

[![FastAPI](https://img.shields.io/badge/Backend-FastAPI-blue?style=for-the-badge)](https://fastapi.tiangolo.com/)  
[![Next.js](https://img.shields.io/badge/Frontend-Next.js-black?style=for-the-badge)](https://nextjs.org/)  
[![Firebase Auth](https://img.shields.io/badge/Auth-Firebase-orange?style=for-the-badge)](https://firebase.google.com/)  
[![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-blue?style=for-the-badge)](https://neon.tech/)  
[![AI-Powered](https://img.shields.io/badge/AI-Gemma/GPT--3.5-green?style=for-the-badge)](https://huggingface.co/)  

---

## **🛠️ Tech Stack**
### **Frontend (Next.js)**
- **Framework:** Next.js (App Router)
- **Styling:** Tailwind CSS
- **Authentication:** Firebase Auth (Google & Email)
- **Hosting:** Vercel

### **Backend (FastAPI)**
- **Framework:** FastAPI
- **Database:** PostgreSQL (Neon.tech)
- **Authentication:** Firebase Admin SDK (JWT Tokens)
- **Hosting:** Render

### **AI Models**
- **Cover Letter Generation:** OpenAI GPT-3.5 (OpenRouter)
- **Property Matching:** Gemma (Google AI) + Vector Search
- **Chatbot:** LangChain

---

## **📌 Features**
✅ **User Authentication** (Google & Email via Firebase)  
✅ **Automated Property Search** (Flatfox API & Web Scraping)  
✅ **AI-Powered Cover Letter Generation** (GPT-3.5)  
✅ **Automated Rental Applications**  
✅ **Document Upload & Verification** (Firebase Storage)  
✅ **AI-Powered Property Matching**  

---

## **🚀 Getting Started**
### **1️⃣ Clone the Repository**
```bash
git clone git@github.com:Kogulan1/ai-house-rental-assistant.git
cd ai-house-rental-assistant
```

### **2️⃣ Set Up the Backend (FastAPI)**
```bash
cd backend
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```
📌 **API is available at:** `http://127.0.0.1:8000`

### **3️⃣ Set Up the Frontend (Next.js)**
```bash
cd frontend
npm install
npm run dev
```
📌 **Frontend is available at:** `http://localhost:3000`

---

## **📌 API Documentation**
FastAPI automatically generates **Swagger API docs**:  
🔗 [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)  

---

## **📌 Environment Variables**
Create a `.env` file in `backend/` and `frontend/` with the following variables:

### **Backend (`backend/.env`)**
```ini
DATABASE_URL=postgresql://your-db-user:your-db-password@your-db-host/your-db-name
SECRET_KEY=your-secret-key
FIREBASE_CREDENTIALS=path/to/firebase-service-account.json
```

### **Frontend (`frontend/.env.local`)**
```ini
NEXT_PUBLIC_FIREBASE_API_KEY=your-api-key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your-auth-domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your-project-id
```

---

## **📌 Contributing**
👨‍💻 **How to Contribute:**
1. **Fork the repository**
2. **Create a feature branch:**
   ```bash
   git checkout -b feature/new-feature
   ```
3. **Commit your changes:**
   ```bash
   git commit -m "Added new feature"
   ```
4. **Push to GitHub & Open a Pull Request**
   ```bash
   git push origin feature/new-feature
   ```
5. **Wait for Review & Merge!** 🚀

---

## **📌 License**
📝 This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## **📌 Contact**
🔗 **GitHub:** [@Kogulan1](https://github.com/Kogulan1)  
📧 **Email:** your-email@example.com  



