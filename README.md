# 🗳️ myVoice API

**Civic participation, structured.**  
A backend platform where citizens can submit issues, vote on proposals, and engage in democratic dialogue — built with FastAPI + PostgreSQL.

---

## 🚀 What It Does

- **Submit civic issues:** Users can raise local or national concerns
- **Vote on proposals:** Upvote or downvote ideas based on community interest
- **Comment system:** Users can discuss and refine proposals
- **Admin tools:** Moderation and approval layers for transparency (planned)

---

## 🎯 Why I Built It

Democratic feedback systems are often noisy, disorganized, and inaccessible.  
I wanted to create a clear, structured API-first platform for civic engagement — where real issues can rise through community voice, not chaos.

This is part of a broader goal to build tech for public good.

---

## 🛠️ Tech Stack

- **Backend:** FastAPI, Pydantic, SQLAlchemy
- **Database:** PostgreSQL
- **Tools:** Uvicorn, Alembic (optional), GitHub

---

## 🧪 Project Structure


---

## 📦 Installation

1. **Clone the repo**  
```bash
git clone https://github.com/1ndrayu/myVoice-api.git
cd myVoice-api
```

2. Set up virtual environment
```
python -m venv env
source env/bin/activate  # On Windows: .\env\Scripts\activate
```

3. Install dependencies
```
pip install -r requirements.txt
```
4. Set up PostgreSQL
  Create a DB and add connection URL to .env

5. Run the API
```
uvicorn main:app --reload
```
---
Coming Soon
- Authentication (JWT or OAuth2)
-  Frontend (React or simple HTML)
-  Analytics dashboard
-  Public API Explorer (Swagger docs are live)

---

If you're interested in civic tech or backend systems, feel free to fork and build.
