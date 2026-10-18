# 📊 AcademicPulse: Interactive Student Analytics Dashboard

[![Live Demo](https://img.shields.io/badge/Demo-Live_Website-success?style=for-the-badge&logo=googlechrome)](https://raoabullah.github.io/studentdashboard/)
[![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla_ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/)
[![HTML5 & CSS3](https://img.shields.io/badge/Frontend-HTML5_&_CSS3-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

AcademicPulse is a responsive, web-based Student Information and Learning Analytics Dashboard. It provides students with unified tracking of course progress, credit hour calculations, study task management, and customizable workspace settings.

---

## 🌟 Key Features

* **Multi-Page Academic Portal:** Includes an executive overview page (`index.html`) and dedicated curriculum manager (`courses.html`).
* **Client-Side State Persistence:** Utilizes browser `localStorage` to save study reminders and custom profile preferences across browser reloads without server overhead.
* **Instant Dynamic Theme Engine:** Seamless Light/Dark mode switcher modifying CSS root variables in real time.
* **Interactive Profile Customization:** Custom image upload preview via JavaScript `FileReader` API with smooth fade-in transitions.
* **Course Completion & Grade Tracking:** Tabular tracking of enrolled courses, instructors, credit hours, and completion metrics.
* **Responsive Layout:** Adaptive desktop and mobile viewports using modern CSS Grid and Flexbox.

---

## 📂 File Structure

```text
studentdashboard/
├── index.html        # Main analytics overview dashboard
├── script.js         # Core dashboard interactions, theme engine, and reminders
├── courses.html      # Course tracking and syllabus overview
├── courses.js        # Course data handling and table rendering
├── styles.css        # Clean UI styling, theme definitions, and animations
├── profile.png       # Default profile avatar asset
└── README.md         # Project documentation
```

---

## 🚀 Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/RaoAbullah/studentdashboard.git
   cd studentdashboard
   ```
2. Open `index.html` directly in any web browser.
3. Or view the live deployment at [raoabullah.github.io/studentdashboard](https://raoabullah.github.io/studentdashboard/).

---

## 👤 Author
* **Rao Abdullah Nasir** — [GitHub](https://github.com/RaoAbullah) · [LinkedIn](https://www.linkedin.com/in/rao-abdullah-rajput) · [Email](mailto:abdullahnasirrao7@gmail.com)
