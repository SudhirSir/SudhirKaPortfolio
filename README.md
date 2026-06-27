# 🚀 Sudhir Singh | Professional Portfolio

> **Software Developer, Data Analyst & AI/ML Enthusiast**
>
> Welcome to my professional portfolio website! This repository houses the source code for my modern, highly interactive, and responsive portfolio designed to showcase my academic background, technical skills, professional experience, projects, certifications, and competitive programming achievements.
>
> 🌐 **Live Website:** [sudhirtutorials.me](https://www.sudhirtutorials.me)
> 📧 **Contact Email:** [sudhir@sudhirtutorials.me](mailto:sudhir@sudhirtutorials.me)

---

## ✨ Key Features

* 🌓 **Dynamic Theme Toggle**: Premium dark mode theme with neon accents and a minimal, elegant light mode theme.
* 🌌 **3D Particle Background**: Responsive interactive canvas background with mouse-repel particles that adapt color dynamically to light/dark themes.
* 🔮 **Custom Cursor**: A glowing custom cursor dot and delayed circular outline with smooth animations and hover states.
* 📱 **Mobile & Tablet Responsive**: Optimized fluid grid layouts for projects, coding profiles, and education, featuring a mobile-friendly slide-in navbar.
* 📧 **Interactive Contact Form**: Direct client communication integrated with **EmailJS** for contact form submissions.
* ⚡ **3D Card Tilt**: Smooth 3D card tilt interactions powered by **Vanilla-Tilt.js** on projects, skills, and certifications.

---

## 🛠️ Tech Stack & Libraries

* **Frontend Structure & Logic:** HTML5, CSS3, JavaScript (Vanilla ES6+)
* **3D Visual Effects:** Vanilla-Tilt.js, HTML5 Canvas API
* **Iconography & Fonts:** Font Awesome v6, Google Fonts (Outfit & Space Grotesk)
* **Form Services:** EmailJS API
* **Hosting/Deployment:** GitHub Pages / Vercel

---

## 📂 Repository Structure

```text
Portfolio/
│
├── index.html            # Main markup file containing portfolio sections
├── style.css             # Custom CSS variables, tokens, layouts, and responsive queries
├── script.js            # Custom interactive JavaScript, canvas logic, and form setup
├── sudhirsir.jpg         # Profile photograph (Cinematic Card)
└── README.md             # Project documentation (this file)
```

---

## 📖 Sections Walkthrough

### 1. Hero / Header
An eye-catching spatial portrait and tagline introducing my specialties in Data Science and AI/ML, alongside quick links to download my CV, view projects, or send an email.

### 2. Technical Arsenal (Skills)
Grouped tags highlighting expertise in Programming (Java, C++, Python, JavaScript, SQL), Web & Backend (REST APIs, Spring Boot, Flask, React, HTML/CSS, Gemini APIs), Machine Learning (Pandas, NumPy, Scikit-learn, LLMs, RAG), Databases & Cloud (MySQL, PostgreSQL, AWS, Azure, Firebase, Hadoop), and core Tools.

### 3. Professional Journey (Experience)
A linear timeline showcasing my work history, including my role as the **Founder and Maths Educator at SUDHIR TUTORIALS** (Since 2019) and my experience as a **Cyber Intern at Uttar Pradesh Police** (OSINT, cyber-fraud analysis, and digital forensics).

### 4. Featured Innovations (Projects)
Responsive cards showing my top projects with custom interactive hover overlays including links to live demos and GitHub repositories:
* **Bias Buster** (React, Flask, GROQ API, Llama 3)
* **EduPred AI** (Python, Scikit-learn, Flask REST API, Power BI)
* **SUDHIR TUTORIALS** (Next.js, React, Node.js, Express, PostgreSQL, Prisma, Capacitor)
* **Digital Munim Ji** (Next.js, React, TypeScript, Tailwind, ShadCN UI, PostgreSQL, Prisma)

### 5. Licenses & Certifications
Verifiable credentials including ChatGPT-4 Prompt Engineering (Infosys), Machine Learning (LPU), Cloud Computing (NPTEL), and clickable links to my **Oracle Data Foundation Associate** and **Oracle AI Foundation Associate** credentials.

### 6. Coding Profiles
Direct links to my profiles across top competitive programming platforms featuring official SVG logos:
* **GeeksforGeeks** (300+ DSA Problems solved)
* **LeetCode** (Competitive Programming)
* **CodeChef** (Silver Badge Problem Solver)
* **HackerRank** (Skills & Certifications)
* **Codeforces** (Competitive Contests)

---

## ⚙️ Getting Started & Setup

### Local Installation

To run this website locally, simply clone the repository and open `index.html` in your browser:

```bash
# Clone the repository
git clone https://github.com/SudhirSir/Portfolio-Website.2.git

# Navigate into the project folder
cd Portfolio-Website.2
```

### Configuring the Contact Form (EmailJS)

To receive messages from the contact form directly to your inbox, you can configure EmailJS:
1. Create a free account on [EmailJS](https://www.emailjs.com/).
2. Add an Email Service (e.g. Gmail) and save your **Service ID**.
3. Create an Email Template and save your **Template ID**.
4. Navigate to `script.js` and replace the placeholder keys:
   ```javascript
   emailjs.init('YOUR_PUBLIC_KEY'); // Line ~313
   
   emailjs.send('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', templateParams) // Line ~348
   ```

---

## 🤝 Contributing

Contributions, suggestions, and feedback are always welcome! Feel free to open an issue or submit a pull request.

---

## 🌟 Support

If you like this portfolio or found it helpful for building your own, consider giving this repository a ⭐!

**Made with ❤️ by Sudhir Singh**
