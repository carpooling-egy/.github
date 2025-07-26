# 🚘 3alsekka Carpooling System

**3alsekka** is a microservices-based carpooling system that connects drivers and passengers heading in the same direction. Designed to promote sustainable transportation and reduce traffic congestion through efficient ride-sharing.

This system was developed as part of the **Computer and Systems Engineering graduation project (Class of 2025)** at **Alexandria University**.

---

## 👥 Team Members

- [Mariam Elsamni](https://www.linkedin.com/in/mariam-elsamni-592184252/)  
- [Mariam Gerges](url)  
- [Marwan Essam](url)  
- [Mohamed Anwar](url)  
- [Hussein Mansour](https://www.linkedin.com/in/hussein-mohamed-5800b4221/)  
- [Hussein Khaled](https://www.linkedin.com/in/husseinkhaled733/)  

---

## 👩‍🏫 Supervisor

- **Dr. Samia Hafez** – Associate Professor, Computer and Systems Engineering Department, Alexandria University

---


## 🛠️ Tech Stack

| Layer         | Technology |
|---------------|------------|
| **Frontend**  | Flutter|
| **Map**  | Mapbox SDK|
| **Backend**   | Go, Spring Boot (Java), Python |
| **Database**  | PostgreSQL, MySQL |
| **Message Channel** | NATS JetStream |
| **Infrastructure & Deployment** | Docker, Azure, GitHub Actions |
| **Routing Engine**   | OSRM, Valhalla |
| **API Gateway**   | APISIX |
| **Architecture Style** | Microservices |
| **Optimization Solver**   | OR-Tools |

---

## 🏗️ System Architecture

<img src="https://github.com/user-attachments/assets/8bd8e8b2-c4e0-4bfc-9398-9a35370dee97" alt="System Architecture" width="100%" />

### 🔍 Architecture Breakdown

| Component | Responsibility |
|----------|----------------|
| **Profile Service** | Manages user profiles: creation, update, and enrichment. |
| **Request Management Service** | Handles ride requests and driver offers, including validation. |
| **Trip Management Service** | Displays and manages upcoming trips for both drivers and passengers. |
| **Matching Job** | Scheduled background job that performs ride-matching logic. |
| **Scheduler** | Controls the timing and execution of the matching job. |

---

## 📁 Repository Structure

Each microservice is hosted in a dedicated repository within this organization:

| Repository | Description |
|------------|-------------|
| [`matching-engine`](https://github.com/carpooling-egy/matching-engine) | Implements the ride-matching algorithm that pairs offers and requests. |
| [`request-management`](https://github.com/carpooling-egy/request-management) | Validates and stores ride requests and driver offers. |
| [`trip-management`](https://github.com/carpooling-egy/trip-management) | Manages the lifecycle and display of upcoming trips. |
| [`profile`](https://github.com/carpooling-egy/profile) | Handles user profile operations. |
| [`frontend`](https://github.com/carpooling-egy/frontend) | Flutter-based mobile frontend of the application. |
| [`authentication`](https://github.com/carpooling-egy/authentication) | Manages user authentication and security. |
| [`api-gateway`](https://github.com/carpooling-egy/api-gateway) | The main entry point to route requests to the appropriate microservices. |
| [`infra`](https://github.com/carpooling-egy/infra) | Contains infrastructure configuration such as networking and channels. |

> 🔎 **Note:** For more details on each repository, refer to its respective `README.md`.

---

## 📱 Application Screenshots

Below are screenshots of the user interface developed using Flutter:

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/1be9c85d-0559-4273-83b8-b451332299d0" width="200"/></td>
    <td><img src="https://github.com/user-attachments/assets/a6bd37af-bf09-4238-b2cc-3ea1d32cd99e" width="200"/></td>
    <td><img src="https://github.com/user-attachments/assets/613b8b9e-fccc-47d9-9255-5b12fe11a07e" width="200"/></td>
    <td><img src="https://github.com/user-attachments/assets/26ad472c-c603-4a1b-ad14-fc1f8a7de422" width="200"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/9ca91caa-5971-4eed-91b6-f3b32902b54d" width="200"/></td>
    <td><img src="https://github.com/user-attachments/assets/55bfdcbb-b8d2-4684-a1de-a87d4dfa511c" width="200"/></td>
    <td><img src="https://github.com/user-attachments/assets/ba6c659c-25e7-408a-a830-3792bacf78dc" width="200"/></td>
    <td><img src="https://github.com/user-attachments/assets/ea1daff7-026c-4978-a1fa-384a176fcd5e" width="200"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/ff28432f-0aab-4410-8d70-28ab4c730a91" width="200"/></td>
    <td><img src="https://github.com/user-attachments/assets/40bdc671-2e62-481a-b64f-08823a47df9c" width="200"/></td>
    <td><img src="https://github.com/user-attachments/assets/ecbceddf-b27f-4b27-8f3c-3aa81c1d9217" width="200"/></td>
    <td><img src="https://github.com/user-attachments/assets/11c3fce9-53ab-442f-b01b-b5cd05648498" width="200"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/b03c6609-4d1e-43ae-b449-3d03f8530ebe" width="200"/></td>
  </tr>
</table>

---

## 🎬 Demo
[Watch the Demo Video](https://drive.google.com/file/d/1bmU6MVYZqPHr-9wY2w992_5zYdxZUHMF/view?usp=sharing)

