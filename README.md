# 🚀 Likhitha Yelubandi — Personal Portfolio & Interactive Build Game

A modern, responsive personal portfolio website built to showcase my technical skills, projects, and educational background as a third-year Computer Science and Engineering student. This project features interactive elements like a **Tech Superpower Skill Picker** and a custom browser minigame called **"Ship It!"**, deployed entirely on **AWS Amplify Hosting**.

Built for the **AWS Student Builder Challenge**.

---

## ✨ Key Features

* **About Me Section:** Background on my CSE studies, placement preparation, and technical focus areas.
* **Interactive Skill Superpower Picker:** Click any skill (Python, JavaScript, React, REST APIs, AI APIs, AWS) to instantly highlight matching projects or view upcoming learning milestones.
* **Featured Projects Showcase:** Highlights full-stack apps, AI-powered tools (like a resume scanner and skill gap roadmap generator), and dashboards with live links and GitHub repositories.
* **"Ship It!" Minigame:** An interactive HTML5 canvas game where you control the Amplify build server to catch commits and clouds while dodging bugs.
* **Architecture Diagram:** Interactive visual breakdown of the deployment pipeline from local development to cloud hosting.
* **Dark / Light Mode Toggle:** Seamless theme switching with state persistence via `localStorage`.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Custom Properties / Variables, Grid, Flexbox), Vanilla JavaScript (ES6+)
* **Styling & Fonts:** Google Fonts (*Syne* & *DM Sans*)
* **Deployment & Hosting:** AWS Amplify Hosting
* **Version Control:** Git & GitHub

---

## ☁️ Deployment Architecture

This portfolio follows a simple, automated cloud-native deployment workflow using **AWS Amplify Hosting**:

1. **Development:** Code changes are written locally and pushed to this **GitHub** repository[cite: 1].
2. **CI/CD:** **AWS Amplify Hosting** automatically detects the repository push, builds the static asset, and provisions it globally over HTTPS[cite: 1].
3. **Delivery:** Visitors access the live, high-performance web app via the secure Amplify public URL[cite: 1].

---

## 📂 Project Structure

```text
├── index.html        # Main single-file source code (HTML, CSS, and Client-side JS Game)
└── README.md         # Project documentation

👩‍💻 Author 
Likhitha Yelubandi
Third-Year B.Tech Computer Science and Engineering Student
GitHub: https://github.com/likhithasitadevi
