# 🚀 Prakhar Sharma — Portfolio

## A modern, dark-themed personal portfolio website showcasing my work as a **MERN Stack Engineer**. Built with **React 19**, **Tailwind CSS v4**, and **Vite**.

## ✨ Sections

| Section          | Description                                                       |
| ---------------- | ----------------------------------------------------------------- |
| **Hero**         | Animated intro with profile photo, tech marquee, and social links |
| **About**        | Personal background and skill highlights                          |
| **Projects**     | Featured work with live + GitHub links                            |
| **Experience**   | Career timeline — currently at Katonic AI                         |
| **Testimonials** | What others say about working with me                             |
| **Contact**      | Email form powered by EmailJS                                     |

---

## 🛠️ Tech Stack

- **Framework:** React 19
- **Styling:** Tailwind CSS v4
- **Build Tool:** Vite (rolldown-vite)
- **Icons:** Lucide React
- **Email:** EmailJS (`@emailjs/browser`)
- **Deployment:** Vercel / Netlify

---

## 📁 Project Structure

```
prakhar-portfolio/
├── public/
│   ├── hero-bg.jpg              # Hero background image
│   ├── prakhar-cropped.png      # Profile photo
│   └── projects/                # Project screenshots
│       ├── nexus.png
│       ├── tailorui.png
│       ├── spotify.png
│       └── edusity.png
├── src/
│   ├── components/
│   │   ├── Button.jsx
│   │   └── AnimatedBorderButton.jsx
│   ├── layout/
│   │   └── Navbar.jsx
│   ├── sections/
│   │   ├── Hero.jsx
│   │   ├── About.jsx
│   │   ├── Projects.jsx
│   │   ├── Experience.jsx
│   │   ├── Testimonials.jsx
│   │   └── Contact.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── .env                         # EmailJS credentials (never commit this!)
├── vite.config.js
├── package.json
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v18+
- npm

### Installation

1. **Clone the repo**

   ```bash
   git clone https://github.com/prakharsharma13/prakhar-portfolio.git
   cd prakhar-portfolio
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Set up environment variables**

   Create a `.env` file in the root and add your EmailJS credentials:

   ```env
   VITE_EMAILJS_SERVICE_ID=your_service_id
   VITE_EMAILJS_TEMPLATE_ID=your_template_id
   VITE_EMAILJS_PUBLIC_KEY=your_public_key
   ```

4. **Start the dev server**

   ```bash
   npm run dev
   ```

   Open `http://localhost:5173` in your browser.

---

## 📦 Available Scripts

| Command           | Description                  |
| ----------------- | ---------------------------- |
| `npm run dev`     | Start development server     |
| `npm run build`   | Build for production         |
| `npm run preview` | Preview the production build |
| `npm run lint`    | Run ESLint                   |

---

## 🌐 Featured Projects

| Project                                           | Tech                             | Links                                                                                                             |
| ------------------------------------------------- | -------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| **Nexus AI** – AI chat app with Google Gemini API | React, Node.js, Express, MongoDB | [Live](https://nexus-ai-five-rosy.vercel.app/) · [GitHub](https://github.com/prakharsharma13/MERN-AI-GPT)         |
| **TailorUI** – Next.js marketing landing page     | Next.js, Shadcn UI               | [Live](https://tailor-ui-prakhar.vercel.app/) · [GitHub](https://github.com/prakharsharma13/TailorUI)             |
| **Spotify Clone** – Music streaming UI            | React, Tailwind CSS              | [Live](https://prakhar-spotify.netlify.app/) · [GitHub](https://github.com/prakharsharma13/React-Music-App)       |
| **Edusity** – University landing page             | React                            | [Live](https://prakhar-edusity-react.netlify.app/) · [GitHub](https://github.com/prakharsharma13/Edusity-ReactJS) |

---

## 🌐 Deployment

Deploy in seconds with:

- **[Vercel](https://vercel.com/)** — Recommended. Connect your GitHub repo for automatic CI/CD.
- **[Netlify](https://netlify.com/)** — Drag & drop the `dist/` folder or connect via Git.

> ⚠️ **Important:** Add your `.env` variables in your deployment platform's environment settings so EmailJS works in production.

---

## 📬 Contact

**Prakhar Sharma** — MERN Stack Engineer

- 📧 [prakharsharma752@gmail.com](mailto:prakharsharma752@gmail.com)
- 💼 [linkedin.com/in/prakhar-sharmaa](https://www.linkedin.com/in/prakhar-sharmaa/)
- 🐙 [github.com/prakharsharma13](https://github.com/prakharsharma13)

---

> Made with ❤️ by Prakhar Sharma — React · Tailwind CSS · Vite
