# Sanket Sharma — Data Analyst Portfolio

## 🖥️ Open Locally (double-click method)
Just double-click `index.html` — opens directly in any browser. No server needed.

## 🚀 Deploy to Vercel (3 steps)

### Step 1 — Push to GitHub
```bash
git init
git add .
git commit -m "portfolio launch"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/sanket-portfolio.git
git push -u origin main
```

### Step 2 — Connect to Vercel
1. Go to https://vercel.com → Sign up free
2. Click **"Add New Project"**
3. Import your GitHub repo `sanket-portfolio`
4. Click **Deploy** — live in ~30 seconds ✅

### Step 3 — Add Your Resume
- Export your resume as `resume.pdf`
- Place it in this same folder (next to `index.html`)
- Git commit & push → auto re-deploys

## 📁 Files
```
sanket-portfolio/
├── index.html     ← Complete portfolio (CSS + JS all in one file)
├── vercel.json    ← Vercel config
├── resume.pdf     ← ADD THIS: your resume PDF
└── README.md
```

## 🎨 Customize
All content is in `index.html`. Search (Ctrl+F) for any text to edit it.
Colors are CSS variables at the top of the `<style>` tag — change `--accent: #1a6ef5` to change the blue.

## 📧 Make Contact Form Send Real Emails
1. Sign up free at https://formspree.io
2. Create a form → copy your endpoint URL
3. In `index.html`, find `<form class="contact-form" id="contactForm" onsubmit="handleSubmit(event)">`
4. Change to: `<form class="contact-form" action="https://formspree.io/f/YOUR_CODE" method="POST">`
5. Remove the `onsubmit` attribute and the `handleSubmit` JS function
