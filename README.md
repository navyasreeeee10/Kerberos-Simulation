# 🎓 Kerberos Simulation for University Login System

This project is a **Python-based Kerberos Authentication Simulation** demonstrating secure login in a university environment using encrypted tickets and session keys.  
It showcases the message flow between **Client**, **Authentication Server (AS)**, **Ticket Granting Server (TGS)**, and **Service**.

---

## 🔍 Overview

Kerberos is a trusted authentication protocol that uses **symmetric key cryptography** to provide secure identity verification over insecure networks.  
This simulation models the Kerberos workflow, including:
- Client requesting authentication from AS  
- AS issuing Ticket-Granting Ticket (TGT)  
- Client requesting service access from TGS  
- TGS issuing Service Ticket  
- Client accessing the service securely using session keys  

---

## ⚙️ Features

- Step-by-step message exchange simulation  
- AES-GCM encryption for confidentiality & integrity  
- Password-based key derivation (PBKDF2-HMAC-SHA256)  
- Timestamp validation to prevent replay attacks  
- Jupyter Notebook / Python script friendly  

---

## 🧠 Components

| Component | Description |
|------------|-------------|
| **Client** | Requests authentication and services |
| **AS (Authentication Server)** | Verifies user credentials and issues Ticket_TGS |
| **TGS (Ticket Granting Server)** | Issues service-specific tickets |
| **Service** | Validates tickets and grants access |

---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Kerberos-University-Simulation.git
   cd Kerberos-University-Simulation

