# 🚀 Deployment Phase

## 🎯 Objectives

- High availability
- Scalability
- Security
- Zero downtime

---

## 🧱 Infrastructure

Provision using:
- Bicep / Terraform

Resources:
- AKS
- SQL / Cosmos DB
- Event Hub / Service Bus
- APIM
- Key Vault

---

## ☸️ AKS Design

### Node Pools
- System
- General
- AI (GPU)

### Scaling
- HPA (pods)
- Cluster autoscaler
- KEDA (event-based)

---

## 🔄 CI/CD Pipeline

1. Build
2. Dockerize
3. Push to ACR
4. Deploy to AKS

---

## 🔐 Security

- Private networking
- RBAC
- TLS everywhere

---

## 📊 Monitoring

- Azure Monitor
- App Insights

---

## 🌍 Disaster Recovery

- Multi-region (Active-Passive)
- Front Door failover
