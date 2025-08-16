# 📘 Microservices - Port Mapping

This project contains multiple microservices with the following port configurations:

| Service         | Port |
|-----------------|------|
| 🛰️ Eureka Server  | **8070** |
| ⚙️ Config Server  | **8888** |
| 🏦 Account Service | **8081** |
| 👤 User Service    | **8082** |
| 💰 Loan Service    | **8083** |
| 💳 Card Service    | **8084** |
| 🌐 API Gateway     | **8085** |

---

## 🚀 Quick Start

1. Start **Config Server** (`8888`)
2. Start **Eureka Server** (`8070`)
3. Start business microservices:
   - Account Service (`8081`)
   - User Service (`8082`)
   - Loan Service (`8083`)
   - Card Service (`8084`)
   - Transaction Service (`8086`)
4. Start **API Gateway** (`8085`)

All client requests should be routed through the **API Gateway**.
