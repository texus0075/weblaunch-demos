# WebLaunch Labs - Cold Outreach Demo Hub

This repository is designed to host your client outreach demo websites using **GitHub Pages CDN**. It provides an instant, fast, and free preview link that you can share with prospective clients.

## 🚀 How to Setup and Deploy on GitHub

Follow these steps to make this folder live on GitHub Pages:

### Step 1: Create a New GitHub Repository
1. Go to your GitHub account: [github.com](https://github.com/)
2. Click the green **"New"** button to create a repository.
3. Name it exactly: **`weblaunch-demos`**
4. Set it to **Public** (important, otherwise GitHub Pages will not be free!).
5. Do NOT initialize with a README, gitignore, or license. Click **"Create repository"**.

### Step 2: Push this folder to GitHub
Open your command prompt or terminal in this folder (`D:\portfolio\weblaunch-demos`) and run these commands:

```bash
git init
git add .
git commit -m "Initialize demo hub with Mewar Clinic"
git branch -M main
git remote add origin https://github.com/texus0075/weblaunch-demos.git
git push -u origin main -f
```

### Step 3: Enable GitHub Pages
1. Go to your new repository page on GitHub: `https://github.com/texus0075/weblaunch-demos`
2. Click on the **Settings** tab (the gear icon on top).
3. In the left sidebar, click on **Pages** (under the "Code and automation" section).
4. Under **"Build and deployment" -> "Source"**, make sure **"Deploy from a branch"** is selected.
5. Under **"Branch"**, select **`main`** and **`/ (root)`**, then click **Save**.

---

## 🔗 Your Live URLs

Once configured, GitHub will deploy your site in less than 1 minute. Your live links will be:

* **Demo Hub Dashboard:**
  `https://texus0075.github.io/weblaunch-demos/`

* **Mewar Clinic Live Preview:**
  `https://texus0075.github.io/weblaunch-demos/demos/mewar-clinic/`

*(No trailing slashes needed, and these links will load instantly across the globe using GitHub's Fastly CDN edge caching!)*
