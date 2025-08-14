🧠 CodeChallengeAssistant
CodeChallengeAssistant is a full-stack AI-powered application that generates multiple-choice coding challenge questions using the LLaMA 3B model. Designed with a clean UI, Clerk authentication system, and AI generation backend, this tool is perfect for learners, educators, and interview preparation platforms.

⚙️ Tech Stack

🔹 Backend

Language: Python
Framework: FastAPI
Database: SQLiite (database.db)
ORM: SQLALCHEMY
AI Model: LLaMA 3B (for question generation)


🔹 Frontend

Language: JavaScript (React)
Bundler: Vite
Authentication: Clerk.dev
HTTP Library: Axios


🚀 Getting Started

✅ Backend Setup
Navigate to the backend:

cd backend
Install dependencies (use your preferred tool):
uv add -r requirements.txt

Start the backend server:
uv run .\server.py
The backend will start at http://localhost:8000


✅ Frontend Setup
Navigate to the frontend:

cd frontend
Install dependencies:

npm install
Start the frontend dev server:

npm run dev
The frontend will start at http://localhost:5173


💡 Features

🔐 User Authentication (via Clerk)
🧠 AI-Powered MCQ Generation using LLaMA 3.3- 70B-Versatile
🧾 MCQ Challenge UI
🕘 User History Panel
📡 FastAPI-based API endpoints
🪄 Minimal & modular UI layout
🌐 CORS-enabled communication between frontend and backend


🧪 Usage
Visit http://localhost:5173
Sign in via Clerk
Navigate to Generate Challenges
Input a topic (e.g., "recursion in Python")
View and interact with the generated MCQs
Check past generated challenges in the History Panel4


📂 Environment Variables
For Clerk auth to work, make sure to add this in your frontend/.env:
VITE_CLERK_PUBLISHABLE_KEY=pk_test_xxxxxxxxxxxxxxxxxxxxxx
Restart the dev server after updating .env.


📄 License
MIT License — feel free to use, modify, and distribute.



