# Divyanshu Chhabra - Portfolio & Resume Website

A modern, responsive, high-performance developer portfolio and interactive resume website built with **HTML5**, **Vanilla CSS3**, and **Modern JavaScript**. Designed with sleek glassmorphism, vibrant neon-glow accents, and ready for 1-click deployment on **Vercel**.

---

## 🌟 Highlights & Features

- **Hero & Identity**: Dynamic typewriter effect, live availability status pill, quick contact pills, and developer config snippet.
- **Skills & Arsenal**: Full-stack web (MERN) and **Mobile App Development** (**Flutter**, **Android Studio**, **Dart**), RESTful APIs, Core CS fundamentals (DSA, OOPs, DBMS, OS, Networking).
- **Featured Projects**:
  - **SmartGPT**: AI conversational chat web app with dynamic UI and real-time LLM endpoints.
  - **Stock Trading Platform**: Full-stack MERN application with real-time stock price tracking, interactive charts, and JWT auth.
- **Education & Certifications**:
  - J.C. Bose University of Science & Technology, YMCA (B.Tech IT: 2023 - 2027)
  - Jain Public School, Rewari (12th: 88.40%, 10th: 94.60%)
  - freeCodeCamp & Simplilearn verified certifications
- **Resume System**:
  - Downloadable official resume file (`Divyanshu_Chhabra_Resume.html`)
  - In-browser instant preview modal
  - Clean `@media print` style sheet for instant **Print / Save as PDF**
- **Approach Me / Contact Section**:
  - 1-click **Copy Email** and **Copy Phone** with animated toast feedback
  - Direct WhatsApp chat link
  - Interactive contact form with mail client handoff

---

## 📁 Project Structure

```text
├── index.html                     # Main interactive portfolio page
├── style.css                      # Modern dark theme & responsive styles
├── script.js                      # Typewriter, modal, clipboard, and form logic
├── Divyanshu_Chhabra_Resume.html  # ATS-friendly, print-ready official resume
├── vercel.json                    # Vercel deployment configuration & security headers
└── README.md                      # Documentation & deployment guide
```

---

## 🚀 How to Deploy on Vercel

### Option 1: Deploy via GitHub (Recommended)

1. Create a new repository on GitHub (e.g., `divyanshu-portfolio`).
2. Push your files to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Portfolio & Resume"
   git branch -M main
   git remote add origin https://github.com/divyanshu-chhabra/your-repo-name.git
   git push -u origin main
   ```
3. Go to [vercel.com](https://vercel.com) and log in with your GitHub account.
4. Click **"Add New"** > **"Project"**.
5. Select your repository and click **"Deploy"**.
6. Vercel will automatically detect the static HTML/CSS/JS site and provide a free live URL (e.g., `https://divyanshu-chhabra.vercel.app`) with free SSL.

### Option 2: Deploy via Vercel CLI

1. Open your terminal in this directory:
   ```bash
   npx vercel
   ```
2. Follow the prompt to log in and select project defaults.
3. For production deployment, run:
   ```bash
   npx vercel --prod
   ```

---

## 💻 Local Testing

You can open `index.html` directly in any web browser, or run a local web server:

```bash
# Using Python
python -m http.server 8080

# Or using Node.js npx serve
npx serve .
```

Open `http://localhost:8080` in your browser.
