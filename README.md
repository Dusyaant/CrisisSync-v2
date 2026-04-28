# 🛰️ CrisisSync v2: Real-Time Emergency Response System

**CrisisSync v2** is a decentralized, real-time coordination platform designed to bridge the gap between affected civilians and emergency responders during natural disasters. Built for the **Google Solution Challenge**, this platform leverages real-time geospatial data and AI to optimize rescue efforts when every second counts.

## 🚀 Live Demo
Check out the live application here: **[https://dusyaant.github.io/CrisisSync-v2/](https://dusyaant.github.io/CrisisSync-v2/)**

---

## 🏗️ System Architecture

CrisisSync v2 follows a modern **Serverless Cloud Architecture** to ensure high availability and low latency during critical emergencies.

### 1. Frontend Layer (Client-Side)
* **Web Dashboard:** Built with HTML5/CSS3 and Vanilla JS for maximum speed and compatibility.
* **Geospatial Mapping:** Powered by **Leaflet.js** and OpenStreetMap to render real-time incident pins.
* **State Management:** Local listeners that respond instantly to database changes.

### 2. Backend & Real-Time Layer (Firebase)
* **Authentication:** **Firebase Auth** manages secure login/registration for Responders and Admins.
* **Real-Time Data Pipeline:** **Firebase Realtime Database** acts as the central nervous system, broadcasting SOS signals across all connected clients in under 200ms.
* **Security Rules:** Granular JSON-based rules protect sensitive victim data while allowing public reporting.

### 3. Intelligence Layer (Google Gemini AI)
* **Incident Analysis:** Incoming SOS reports are sent to the **Gemini 1.5 Flash** model.
* **Automated Triage:** The AI categorizes incident severity (SEV-1 to SEV-4) and suggests response protocols based on volume and keywords.
* **Decision Support:** Provides responders with summarized insights to reduce cognitive load during high-stress scenarios.



---

## ✨ Key Features
* **Dual-Portal System:** Dedicated interfaces for **Civilians** (to report emergencies) and **Responder Teams** (to manage resources).
* **Real-Time Incident Mapping:** Dynamic map integration showing live SOS signals with priority levels.
* **Gemini AI Integration:** Automated analysis of incident reports to categorize urgency and suggest response protocols.
* **Interactive SOS Dispatch:** Low-latency communication and automated resource tracking.

## 🛠️ Tech Stack
* **Frontend:** JavaScript (ES6+), Leaflet.js, OpenStreetMap API.
* **Backend:** [Firebase Realtime Database](https://firebase.google.com/products/realtime-database).
* **Auth:** [Firebase Auth](https://firebase.google.com/products/auth).
* **AI:** [Google Gemini API](https://ai.google.dev/).
* **Hosting:** GitHub Pages.

## 📦 Installation & Setup
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Dusyaant/CrisisSync-v2.git](https://github.com/Dusyaant/CrisisSync-v2.git)
    ```
2.  **Setup Firebase:** Create a project, enable Auth/Realtime DB, and update the `firebaseConfig` in `index.html`.
3.  **Run Locally:** Simply open `index.html` in your browser.

## 👥 The Team
* **Dusyaant R** - Lead Developer & UI/UX Design
* **Selvamagal M** - Contributor & System Architect

---

## ⚖️ License
This project is licensed under the MIT License.
