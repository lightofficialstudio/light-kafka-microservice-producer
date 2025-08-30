# ⚡️ Kafka Microservice Producer (NestJS + TypeScript)

[![NestJS](https://img.shields.io/badge/NestJS-v10-red?logo=nestjs&logoColor=white)](https://nestjs.com/)
[![Kafka](https://img.shields.io/badge/Apache%20Kafka-Message%20Queue-black?logo=apachekafka)](https://kafka.apache.org/)
[![Docker](https://img.shields.io/badge/Docker-Ready-blue?logo=docker)](https://www.docker.com/)
[![Typescript](https://img.shields.io/badge/Typescript-5.0-blue?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)

---

## 📌 Introduction
โปรเจกต์นี้เป็น **Microservice Producer** ที่พัฒนาโดยใช้ **NestJS (TypeScript)**  
สำหรับส่งข้อความเข้าสู่ **Kafka Message Queue**  

💡 โปรเจกต์นี้จัดทำขึ้นเพื่อการ **ฝึกฝน (Practice Project)**  
โดยเน้นทำความเข้าใจ **Event-driven Architecture** และการสื่อสารระหว่าง Microservices

---

## ⚙️ Tech Stack
| Tech | Description |
|------|-------------|
| 🟣 **NestJS (TS)** | Backend Framework สำหรับสร้าง Microservices |
| ⚫ **Kafka** | Message Queue สำหรับ Event-driven Architecture |
| 🐳 **Docker** | Containerization & Local Orchestration |
| 📡 **KafkaJS / @nestjs/microservices** | Library สำหรับเชื่อมต่อกับ Kafka |

---

## 🚀 Features
✅ ส่งข้อความ (Produce Message) ไปยัง Kafka Topic  
✅ ใช้ **NestJS Microservice Module** สำหรับ integrate กับ Kafka  
✅ Config ผ่าน `.env` เพื่อปรับค่า **Kafka Broker**, **Topic Name** ได้  
✅ รองรับการต่อขยายไปยัง Consumer Service อื่น ๆ  

---

## ▶️ Getting Started

```bash
# 1. Clone Repo
git clone https://github.com/your-username/kafka-microservice-producer.git
cd kafka-microservice-producer

# 2. Install Dependencies
npm install

# 3. Start Kafka (with Docker)
docker-compose up -d

# 4. Run Producer
npm run start:dev
