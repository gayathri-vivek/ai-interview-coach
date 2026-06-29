# 🤖 AI Interview Coach

An AI-powered technical interview preparation platform built with Spring Boot and Groq LLM.

## 🚀 Features
- ✅ AI-generated role-specific interview questions
- ✅ Intelligent answer evaluation with scoring
- ✅ Strengths & improvement feedback
- ✅ Better answer suggestions
- 🔲 Session history & progress tracking
- 🔲 React dashboard with score charts
- 🔲 Docker deployment

## 🛠️ Tech Stack
| Layer | Technology |
|-------|-----------|
| Backend | Spring Boot 3.3 |
| AI Integration | Spring AI + Groq (LLaMA 3.1) |
| Database | PostgreSQL |
| Frontend | React (in progress) |
| Container | Docker |

## 📡 API Endpoints

### Generate Question
GET /api/interview/question?role=Java Developer&difficulty=Medium

### Evaluate Answer
POST /api/interview/evaluate
{
  "role": "Java Developer",
  "question": "your question here",
  "answer": "your answer here"
}

## ⚙️ Setup
1. Clone the repo
2. Copy application.properties.example → application.properties
3. Add your Groq API key from console.groq.com
4. Run: mvnw spring-boot:run

## 📊 Status
🚧 Backend complete and working | Frontend in progress
