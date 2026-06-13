# Clevision — Corporate Web Platform

Clevision is a modern, single-page corporate website designed with a clean, formal layout and high-performance engineering. It features a responsive landing page and a dynamic, interactive product catalog built with HTML5, Tailwind CSS, and Vanilla ES6+ JavaScript.

## 🚀 Live Preview
To preview the website locally, simply open `index.html` in any modern web browser, or run a local development server in this directory:
```bash
# Using Python
python -m http.server 8000

# Using Node.js http-server
npx http-server -p 8000
```
Then visit: **[http://localhost:8000](http://localhost:8000)**

---

## ✨ Key Features
- **Corporate Styling System**: Clean slate backgrounds, soft borders, and premium Navy Blue and Royal Indigo accents designed to represent high-end office operations.
- **Micro-Animations**: Keyframe floating card animations that react smoothly to user hover and scroll actions.
- **Dynamic Asset Store**: An interactive product catalog showcasing:
  - **Category Tabs**: Filter items instantly by category (Electronics, Clothing, Accessories).
  - **In-Stock Toggle**: Filter out unavailable items dynamically.
  - **Sorting Engine**: Sort products by price (Low to High and High to Low) in real-time.
- **Toast Notifications**: Interactive cart triggers that spawn custom DOM-rendered floating alerts on clicks.
- **Mobile Responsive Drawer**: Sticky glassmorphism header that converts to a collapsible slide-down navigation drawer on smaller viewports.
- **Scroll Spy & Observer**: The navigation links highlight automatically as you scroll down past their respective sections.

---

## 🛠️ Technology Stack
- **Structure**: HTML5 Semantic Markup
- **Styling**: Tailwind CSS (compiled via client-side Play CDN)
- **Logic**: Vanilla ES6+ JavaScript
- **Fonts**: Plus Jakarta Sans (via Google Fonts API)
- **Icons**: Inline scalable SVGs for fast, dependency-free load times

---

## 📁 Directory Structure
```text
Clevision/
├── index.html         # Main single-page application entry point
├── README.md          # Documentation guide
└── assets/
    └── hero.png       # Minimalist corporate workspace hero image
```

---

## ☁️ Deployment (GitHub Pages)
You can deploy this repository for free directly onto **GitHub Pages**:
1. Create a repository on GitHub and push these files:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo-name>.git
   git push -u origin main
   ```
2. On GitHub, go to your repository **Settings** > **Pages**.
3. Under *Build and deployment*, set the branch to `main` (root folder) and click **Save**.
4. Your site will be live within a few minutes!
