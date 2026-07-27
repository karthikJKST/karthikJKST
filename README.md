# Jana Karthik Siva Teja

Software Engineer · Spring Boot · React · PostgreSQL

[LinkedIn](https://linkedin.com/in/karthik-siva-teja-jana-a367a0275) · [Email](mailto:karthikshivatejaj@gmail.com) · [GitHub](https://github.com/karthikJKST) · [Resume](jana_karthik_siva_teja_Resume.pdf)

---

## About

Computer Science undergraduate at VIT-AP building production-grade software. I design and deploy full-stack applications with Spring Boot, React, PostgreSQL, and Docker — focusing on clean architecture, REST API design, authentication systems, and cloud infrastructure.

---

## Engineering

```
Languages:     Java, Python, JavaScript, TypeScript, SQL
Backend:       Spring Boot 3, Spring Security, JPA/Hibernate, JWT, FastAPI, Node.js
Frontend:      React 19, TypeScript, Tailwind CSS, Vite, React Query
Database:      PostgreSQL, MongoDB, SQLite, H2, Flyway
Infrastructure: Docker, Docker Compose, GitHub Actions, Nginx, Vercel, Render
AI/ML:         TensorFlow, Scikit-learn, CNN, Transfer Learning, Gemini API
Tools:         Git, Maven, IntelliJ, Postman, Linux
```

---

## Projects

### WeekDays
Production-grade project management platform with Kanban boards, task tracking, calendar views, and real-time notifications.

**Stack:** Spring Boot 3 · Java 21 · React 19 · TypeScript · PostgreSQL · Docker · JWT · Flyway

**Engineering:**
- JWT authentication with access/refresh token rotation
- Layered architecture: Controllers → Services → JPA Repositories
- Database migrations via Flyway with PostgreSQL
- Multi-stage Docker builds with health checks and non-root user
- Docker Compose orchestration (PostgreSQL + API + Nginx frontend)
- Demo login for instant evaluation

[Source](https://github.com/karthikJKST/WeekDays) · [Live Demo](https://weekdays-gules.vercel.app) · [API Health](https://weekdays-nznb.onrender.com/actuator/health)

---

### StockFlow
Real-time stock market intelligence platform with live quotes, technical analysis indicators, and paper trading.

**Stack:** Spring Boot 3 · Java 21 · React · TypeScript · PostgreSQL · WebSocket · Finnhub API

**Engineering:**
- Real-time price streaming via STOMP WebSocket
- Technical indicators: SMA, EMA, RSI, MACD, Bollinger Bands
- Portfolio tracking with P&L calculation and allocation charts
- Stock screener with multi-criteria filtering
- CI/CD pipeline (GitHub Actions: build, test, typecheck, Docker)
- Graceful fallback from live API to simulated data

[Source](https://github.com/karthikJKST/StockFlow) · [Live Demo](https://stock-flow-ashen.vercel.app)

---

### AI-Career-Assistant
AI-powered interview preparation and resume analysis platform.

**Stack:** FastAPI · Python · React · Gemini API · SQLite · JWT

**Engineering:**
- AI-generated interview questions from resume parsing (PyMuPDF)
- Real-time answer evaluation across 7 scoring dimensions
- ATS resume matching against job descriptions via Gemini
- JWT authentication with rate limiting (SlowAPI)
- Voice support: speech-to-text and text-to-speech
- PDF report generation with performance metrics

[Source](https://github.com/karthikJKST/AI-Career-Assistant)

---

### PHOENIX
AI-powered desktop operating assistant for multi-step task automation.

**Stack:** Python · LLM Integration · Desktop Automation · Speech Recognition

**Engineering:**
- Modular plugin architecture with 20+ action modules
- LLM-based planning engine for multi-step goal decomposition
- Voice command pipeline (speech recognition + TTS)
- Cross-application desktop automation (PyAutoGUI, window management)

[Source](https://github.com/karthikJKST/PHOENIX)

---

### Diabetic Retinopathy Detection
Deep learning system for classifying retinal images.

**Stack:** TensorFlow · CNN · ResNet50 · Python · Flask · OpenCV

**Engineering:**
- Custom CNN and transfer learning (ResNet50) architectures
- Image preprocessing pipeline with OpenCV
- Web interface for model inference
- Flask deployment with gunicorn

[Source](https://github.com/karthikJKST/Diabetic_retinopathy)

---

### Portfolio Website
Personal developer portfolio showcasing projects and skills.

**Stack:** React · JavaScript · CSS · Vite · Framer Motion

**Engineering:**
- Component-based architecture with glassmorphism design
- Intersection Observer-based scroll animations
- Responsive layout system
- Cloudflare Pages deployment

[Source](https://github.com/karthikJKST/karthik-portfolio)

---

## Production Features

Across these projects, I've implemented:

- JWT authentication with refresh tokens
- REST API design with layered architecture
- Database migrations and schema management
- Docker containerization with multi-stage builds
- CI/CD pipelines (GitHub Actions)
- WebSocket real-time communication
- Rate limiting and input validation
- Secure password hashing (BCrypt)
- CORS configuration for production deployment
- Health checks and monitoring endpoints

---

## Currently

**Building:** Advanced Spring Boot patterns — event-driven architecture, CQRS, and message queues.

**Learning:** Kubernetes, system design for distributed applications, advanced testing strategies.

---

## Certifications

- MongoDB Associate Database Administrator — MongoDB (July 2025)
- AI using Google TensorFlow — SmartInternz (2025)

---

*Open to software engineering opportunities. Focused on Java backend, full-stack development, and distributed systems.*
