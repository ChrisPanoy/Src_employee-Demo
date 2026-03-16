# 🚀 GitHub Pages Deployment Guide

This folder contains a fully static version of the **SRC Attendance System**, designed for professional presentations and demo hosting on GitHub Pages.

## 📁 Contents
- `index.html`: Admin Dashboard (Landing Page)
- `login.html`: Login Simulation Page
- `faculty.html`: Faculty Portal Demo
- `live.html`: Live TV Dashboard Simulation
- `css/`: Styling assets
- `assets/`: Image assets (Logos, etc.)

---

## 🛠 Step-by-Step Upload Instructions

### 1. Prepare your GitHub Repository
1. Log in to your GitHub account.
2. Create a new repository (e.g., `src-attendance-demo`).
3. Set the repository to **Public**.

### 2. Upload the Static Files
There are two ways to upload the files:

#### Option A: Using GitHub Desktop (Recommended)
1. Clone the repository to your computer.
2. Copy all files **inside** this `demo` folder into your local repository folder.
3. Commit the changes: "Initial demo upload".
4. Click **Push origin**.

#### Option B: Using the Web Interface
1. Open your repository on GitHub.com.
2. Click **Add file** -> **Upload files**.
3. Drag and drop all files and folders (index.html, css, assets, etc.) from this `demo` folder into the browser window.
4. Click **Commit changes**.

### 3. Enable GitHub Pages
1. Go to your repository **Settings** tab.
2. On the left sidebar, click **Pages**.
3. Under **Build and deployment** -> **Branch**, select `main` (or `master`) and folder `/(root)`.
4. Click **Save**.

---

## 🌐 Accessing the Live Demo
- After saving, GitHub will provide a link: `https://yourusername.github.io/repository-name/`
- It may take 1-2 minutes for the site to go live.
- Refresh the Pages setting page to see the green notification: *"Your site is live at..."*

## 💡 Important Notes
- This version uses **Mock Data**. It does not require XAMPP, PHP, or MySQL.
- All links are **Relative**, ensuring compatibility with GitHub's subdirectory structure.
- To exit the demo, clients can simply close the tab.

---
**Developed for Professional Presentation Excellence.**
