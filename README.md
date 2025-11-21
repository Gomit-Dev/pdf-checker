# PDF Rule Checker – Fullstack Assignment

This is a small fullstack project where the user uploads a PDF and enters 3 rules.  
The backend checks the document against those rules using an LLM and returns:

- pass/fail
- short evidence sentence
- your reasoning
- confidence (0–100)

The goal was to keep things simple and readable.

---

## 🛠 Tech Stack
**Frontend:** React + Vite  
**Backend:** Node.js + Express  
**PDF Parsing:** pdf-parse  
**LLM:** OpenAI-compatible API

---

## 🚀 How to Run

### 1. Backend
-cd backend
-npm install
-cp .env.example .env
-Add your OPENAI_API_KEY in the .env
-npm start
-Backend runs on **http://localhost:4000**

---

### 2. Frontend
-cd frontend
-npm install
-npm run dev
-Frontend runs on **http://localhost:5173**

---

## ✔ Features
- Upload a PDF (2–10 pages)
- Enter up to 3 rules
- Clean table with pass/fail, evidence, reasoning & confidence
- Simple readable backend code

---

## 📸 Screenshot
(Add your screenshot here once you run it locally)

---

## Notes
The project uses a simple approach to PDF text extraction and confidence handling.  
If needed, page-wise extraction can be added later, but for this assignment the current setup works well.

