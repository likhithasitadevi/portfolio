# Developer Portfolio & Interactive Build Game

A lightweight, responsive developer portfolio that showcases my projects, my skills and how the site is deployed. It is built with plain HTML, CSS and JavaScript (no frameworks), includes an HTML5 Canvas mini game, and is deployed automatically with **AWS Amplify Hosting**.

Built for the **AWS Student Builder Challenge: Build Your Tech Superpower**.

---

## Live Demo & Source Code

- **Live Demo:** https://main.d31zwpsvuvb437.amplifyapp.com
- **GitHub Repository:** https://github.com/likhithasitadevi/portfolio

---

## Key Features

- **Skill Picker:** Click a skill chip and the projects that use it are highlighted while the rest fade. Skills without a project yet are marked as "next on my list".
- **"Ship It!" Canvas Game (creative feature):** You play the Amplify build server. Catch commits (+10) and clouds (+30), dodge bugs (lose a life), and level up as the game speeds up. It works with mouse, touch and keyboard, saves your best score in `localStorage`, and ends with a rank from Intern to Deploy Legend.
- **Deployment Diagram:** An SVG diagram showing how this site goes from my laptop to GitHub to AWS Amplify Hosting to the visitor.
- **Light / Dark Theme:** A toggle built on CSS custom properties that remembers your choice and respects your system setting.
- **Responsive and Accessible:** Works from phone to desktop, with keyboard focus styles, ARIA labels and reduced-motion support.

---

## Tech Stack

- **Frontend:** HTML5, CSS (custom properties, Flexbox, Grid), vanilla JavaScript (ES6)
- **Game:** HTML5 Canvas API, `requestAnimationFrame`, high-DPI scaling with `devicePixelRatio`
- **Hosting:** AWS Amplify Hosting
- **Version Control:** Git and GitHub

---

## Deployment on AWS

1. **Push:** I commit my code and push it to the `main` branch on GitHub.
2. **Build and deploy:** AWS Amplify Hosting detects the push, builds the site and publishes it automatically.
3. **Serve:** The site is delivered over HTTPS at a public Amplify URL, with no servers for me to manage.

**AWS service used:** AWS Amplify Hosting

---

## Repository Structure

```text
├── index.html   # Single-file site: HTML structure, CSS and the JavaScript (skill picker, theme, game)
└── README.md    # Project documentation
```

---

## Lessons Learned

- Connecting a GitHub repository to Amplify so every push redeploys the site.
- Building a game loop with Canvas and making it work with mouse, touch and keyboard.
- Designing one layout that works well on both phones and large screens.

---

## Author

**Likhitha Yelubandi**

Third-year Computer Science Engineering student, building web apps and AI tools.

- GitHub: https://github.com/likhithasitadevi
- LinkedIn: https://www.linkedin.com/in/likhitha-yelubandi-698759374/
