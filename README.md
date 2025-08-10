# LucyBounty

> Ethiopia’s First Multilingual Bug Bounty & Cybersecurity Platform

---

<!--
  ===========================
  Project Overview Section
  ===========================
-->
## 📌 Project Overview

**LucyBounty** is Ethiopia’s pioneering bug bounty platform designed to connect ethical hackers with organizations seeking to improve their cybersecurity.  
Inspired by *Lucy* (Dinkinesh), the iconic Ethiopian fossil symbolizing discovery, paired with *Bounty* — rewards for hackers — our platform aims to nurture local talent and secure Ethiopia’s growing digital ecosystem.

---

<!--
  ===========================
  Features Section
  ===========================
-->
## ✨ Features

### Core Features (MVP)
- **Multilingual Support:** Interface and content available in Amharic, English, with plans for Tigrinya and Afaan Oromo.
- **User Roles:** Separate accounts and dashboards for Hackers, Clients (Organizations), and Admins.
- **Bug Bounty Programs:** Clients can create and manage vulnerability disclosure programs.
- **Vulnerability Reporting:** Hackers submit detailed reports including proof of concept and severity levels.
- **Triage & Validation:** Admin panel for security analysts to review, validate, and prioritize reports.
- **Reward System:** Secure payment flow for bounty payouts to hackers.
- **CTF Training Zone:** Interactive Capture The Flag challenges modeled after Hacker101 for skill-building.
- **Awareness Hub:** Educational resources tailored for Ethiopian users and companies.
- **Ethiopian Cultural UI:** Design elements inspired by Ethiopian heritage for a familiar and engaging experience.

---

<!--
  ===========================
  Why LucyBounty Section
  ===========================
-->
## 🔐 Why LucyBounty?

Ethiopia’s digital transformation faces growing cyber threats.  
However, many organizations lack safe, structured channels to receive vulnerability reports. Local ethical hackers often lack legal platforms to showcase skills and earn rewards.  
LucyBounty bridges these gaps by offering a secure, culturally relevant, multilingual platform fostering collaboration, education, and cybersecurity growth.

---

<!--
  ===========================
  Tech Stack Section
  ===========================
-->
## 🛠 Technology Stack

- **Frontend:** React.js with Tailwind CSS for a responsive, modern UI  
- **Backend:** FastAPI (Python) for high-performance APIs and scalability  
- **Database:** PostgreSQL for reliable data storage  
- **Storage:** MinIO (S3-compatible) for secure file uploads  
- **CTF Environment:** Dockerized challenges for isolated and safe hacking practice  
- **Deployment:** Docker containers, suitable for VPS/cloud environments  
- **Version Control:** Git and GitHub for source code management

---

<!--
  ===========================
  Installation & Setup Section
  ===========================
-->
## 🚀 Installation & Setup

### Prerequisites

Make sure you have installed:  
- Node.js (v16+) and npm  
- Python 3.10+ and pip  
- PostgreSQL database  
- Docker (for CTF environment)  

---

### Clone the Repository

```bash
git clone https://github.com/<your-username>/lucy-bounty.git
cd lucy-bounty
Backend Setup

cd backend
python -m venv venv            # Create virtual environment
source venv/bin/activate       # Activate (Linux/macOS)
# .\venv\Scripts\activate      # Activate (Windows)
pip install -r requirements.txt

Set environment variables (e.g., database URL, secret keys) in .env file.

Run the backend server:

uvicorn app.main:app --reload

Frontend Setup

cd frontend
npm install
npm start

The frontend will run at http://localhost:3000 and communicate with the backend API.
Docker Setup (CTF Challenges)

cd ctf/docker
docker-compose up -d

This starts isolated containers for CTF challenges used in training.
<!-- =========================== Usage Section =========================== -->
🎯 Usage

    For Hackers: Register, browse active bug bounty programs, submit vulnerability reports, and practice on CTF challenges.

    For Clients: Register your organization, create and manage bug bounty programs, review vulnerability reports, and reward hackers.

    For Admins: Validate vulnerability reports, manage users and programs, monitor platform activity.

<!-- =========================== Contributing Section =========================== -->
🤝 Contributing

We welcome contributions from the community!
How to contribute:

    Fork the repository.

    Create a feature branch (git checkout -b feature/your-feature).

    Commit your changes (git commit -m 'Add your feature').

    Push to your branch (git push origin feature/your-feature).

    Open a Pull Request describing your changes.

Please follow coding standards and include tests when applicable.
<!-- =========================== License Section =========================== -->
📜 License

This project is licensed under the MIT License. See LICENSE file for details.
<!-- =========================== Team Section =========================== -->
👥 Team Members

    Kidus Yitayal (Team Representative)

    Abdulkamil Kemal Dibaba

    Elias Workneh

    Tsegay Assefa Kidane

Thank you for checking out LucyBounty — together, let’s build a safer Ethiopia!


If you want, I can also help create smaller READMEs for the frontend/backend folders or write a `CONTRIBUTING.md`. Let me know!



