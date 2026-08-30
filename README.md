# 🌸 Digital Baby Shower Invitation (Seemant Sanskar)

A lightweight, standalone, single-page digital invitation website for **Dhara & Sanjay Ramani's Seemant Sanskar (Baby Shower)** on **Sunday, October 18, 2026**.

---

## 📁 What is in this `build/` folder?

This folder contains **everything needed to host the website**:
- **`index.html`**: The complete single-page application (includes 3D interactive royal envelope opening, falling rose petal shower, countdown timer, event summary, Google Calendar one-click add, Google Maps navigation, and embedded Tally RSVP form).
- **`page_1.png` to `page_4.png`**: High-resolution invitation cards.

---

## 💻 How to Run Locally

You can run this website on your computer with any of the following commands:

### Option 1: Python (Built-in on Mac/Linux/Windows)
Open terminal in this `build` directory and run:
```bash
python3 -m http.server 8080
```
Then open: **[http://localhost:8080](http://localhost:8080)**

### Option 2: Node / NPX
```bash
npx -y serve .
```

---

## 🚀 How to Host for Free (Shareable Public Link)

### Method 1: Netlify (Easiest & Fastest — 30 Seconds)
1. Go to **[https://app.netlify.com/drop](https://app.netlify.com/drop)**
2. Drag and drop this entire `build/` folder onto the web page.
3. Your site is instantly live with a free shareable HTTPS link (e.g. `https://dhara-sanjay-seemant.netlify.app`).

---

### Method 2: Vercel (1 Minute)
1. Install vercel CLI or sign in at **[https://vercel.com](https://vercel.com)**.
2. In terminal inside `build/`, run:
   ```bash
   npx vercel
   ```
3. Follow prompts to deploy instantly.

---

### Method 3: GitHub Pages (Free Permanent Hosting)
1. Create a new GitHub repository (e.g. `baby-shower-invitation`).
2. Inside this `build/` folder, run:
   ```bash
   git init
   git add .
   git commit -m "Initial invitation release"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/baby-shower-invitation.git
   git push -u origin main
   ```
3. Go to **GitHub Repository Settings → Pages → Source: Deploy from branch (`main`) → Save**.
4. Your invitation will be live at: `https://YOUR_USERNAME.github.io/baby-shower-invitation/`.

---

## 📝 Connected Services
- **RSVP Form**: Tally Form (`https://tally.so/r/kdBMZM`)
- **Map Location**: Century Gardens Recreation Centre (`https://maps.app.goo.gl/rXhAnAvXR9BEqp4d9`)
- **Date & Time**: Sunday, October 18, 2026 (10:30 AM Ceremony, 12:30 PM Lunch)
