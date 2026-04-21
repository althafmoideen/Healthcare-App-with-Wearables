# 🏗️ Design Phase (Azure Deep Dive)

## 🎯 Architecture Style

👉 Microservices + Event-Driven

---

## 🧱 Architecture Layers

### 1. Client Layer
- Angular Web App
- Mobile App

### 2. API Gateway
- Azure API Management

### 3. Microservices
- Patient Service
- Consultation Service
- AI Service
- Wearable Service
- Notification Service

---

## 🔁 Event-Driven Design

- Event Hub → streaming
- Service Bus → async processing

Example Events:
- HeartRateUpdated
- ConsultationStarted
- RecommendationGenerated

---

## 💾 Data Layer

- Azure SQL → transactional
- Cosmos DB → NoSQL
- Blob Storage → files

---

## 🤖 AI Layer

- Azure ML → training
- API → inference

---

## 📊 Monitoring

- Azure Monitor
- Application Insights

---

## 🔐 Security

- Azure AD (Auth)
- Key Vault (Secrets)
- HTTPS everywhere
