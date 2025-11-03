# 🌍 Twin Travellers — 3-Tier Travel Booking Website

Twin Travellers is a full-stack **3-tier web application** built using **Node.js**, **Express**, **MySQL (AWS RDS)**, and **AWS SES** for sending verification and booking emails.  
The project provides an end-to-end travel booking experience — from **user signup/login with email verification** to **package booking with email confirmation**.

---

## 🧱 Project Architecture

**Tier 1: Frontend (Presentation Layer)**  
- HTML, CSS, JavaScript  
- Hosted on the same EC2 instance (served via Express static middleware)  
- Pages: `index.html`, `login.html`, `register.html`, `booking.html`, `locations.html`, `contact.html`

**Tier 2: Backend (Application Layer)**  
- Node.js + Express.js  
- API routes for authentication and booking  
- Email sending via AWS SES  
- JWT authentication

**Tier 3: Database (Data Layer)**  
- MySQL database hosted on **AWS RDS**
- Stores user credentials and booking details

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | HTML, CSS, Vanilla JavaScript |
| Backend | Node.js, Express.js |
| Database | MySQL (AWS RDS) |
| Email Service | AWS Simple Email Service (SES) |
| Hosting | AWS EC2 (Ubuntu 22.04) |
| Environment Variables | dotenv |
| Authentication | JSON Web Tokens (JWT) |

