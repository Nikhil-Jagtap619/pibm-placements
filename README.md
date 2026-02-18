# PIBM Secure Placement Vault 🛡️

A secure, authenticated web portal developed for the **PIBM** student community. This application serves as a restricted repository for sensitive job descriptions, ensuring that placement data remains within the institutional ecosystem.

## 🚀 [Live Demo Link]

## 💡 The Problem
PIBM campus Job Descriptions are always a pain in a$$ and unorganised.
This portal helps pibm students to understand what companies have been through campus and what they seek, therefore the juniors can be prepared for their desired Role|Comapany.

## 🛠️ The Solution (Tech Stack)
- **Frontend:** HTML5, Tailwind CSS, JavaScript (ES6+).
- **Backend-as-a-Service:** **Firebase Firestore** for real-time data management.
- **Identity Management:** **Firebase Authentication** (OAuth 2.0) with domain-restricted logic.
- **CI/CD & Security:** **GitHub Actions** for automated secret injection and deployment.

## 🛡️ Key Security Features
* **SSO Domain Restriction:** Only authenticated users with a verified `@pibm.in` email can bypass the security gate.
* **Server-Side Security Rules:** Implemented **Firestore Security Rules** to prevent unauthorized data fetching, even if the API keys are discovered.
* **"Blur-on-Blur" Technology:** The application utilizes focus-detection logic; if a user switches tabs or opens a screen-capture tool, the content instantly blurs.
* **Deterrence Layer:** Disabled right-click, text selection, and common print/save keyboard shortcuts.
* **Secret Masking:** API credentials are never stored in the repository. They are injected during the build process via GitHub Secrets.

---
**Developed by lazynikh | Google Campus Ambassador**
