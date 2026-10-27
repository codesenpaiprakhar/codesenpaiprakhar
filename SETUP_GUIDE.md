# 🚀 Deployment Guide for Prakhar Singh (@codesenpaiprakhar)

Your GitHub profile README has been designed to replicate the exact luxury dark & amber aesthetic from your reference image, complete with vector SVGs, custom buttons, engineering philosophy, and real-time telemetry.

---

## 📁 Repository Structure

Ensure all these files are committed and pushed to your **`codesenpaiprakhar/codesenpaiprakhar`** repository:

```text
codesenpaiprakhar/
├── .github/
│   └── workflows/
│       └── snake.yml         # Generates contribution eating snake
├── assets/
│   ├── header.svg            # Hero banner card (Prakhar Singh • Software Engineer)
│   ├── philosophy.svg        # Engineering Philosophy card (System Design, Correctness, API Boundaries)
│   ├── tech-stack.svg        # Technical Capabilities card (Languages, Backend, ML, DevOps)
│   ├── btn-portfolio.svg     # Amber PORTFOLIO button
│   ├── btn-linkedin.svg      # Amber LINKEDIN button
│   ├── btn-email.svg         # Amber EMAIL button
│   ├── btn-leetcode.svg      # Amber LEETCODE button
│   └── btn-github.svg        # Amber GITHUB button
├── README.md                 # Main profile markdown
└── SETUP_GUIDE.md
```

---

## 🚀 How to Deploy in 3 Steps

### Step 1: Create the Secret Profile Repository
1. Go to [github.com/new](https://github.com/new).
2. Set the repository name to:
   ```text
   codesenpaiprakhar
   ```
3. Ensure it is set to **Public**.
4. Check **Add a README file** (or leave empty if pushing via terminal).
5. Click **Create repository**.

### Step 2: Push All Files & Assets to GitHub
Open your terminal (PowerShell or Bash) and run:

```bash
cd "C:\Users\hp\.gemini\antigravity\scratch\github-profile-readme"
git init
git add .
git commit -m "feat: luxury dark & amber profile readme with vector cards"
git branch -M main
git remote add origin https://github.com/codesenpaiprakhar/codesenpaiprakhar.git
git push -u origin main --force
```

> **Important:** The `assets/` folder contains your banner, philosophy, tech stack, and button SVGs. Pushing the entire directory makes them render sharply on GitHub across desktop and mobile.

### Step 3: Enable the Contribution Snake Action
1. On your GitHub repository page, go to **Settings** > **Actions** > **General**.
2. Scroll down to **Workflow permissions**.
3. Select **"Read and write permissions"** and click **Save**.
4. Go to the **Actions** tab, select **Generate Snake Animation**, and click **Run workflow**.

---

## 🎨 Customizing Details

- **Profile Bio (in left sidebar):**
  On your GitHub profile page, click **Edit profile** on the left and set your bio to match your resume:
  ```text
  B.Tech CSE student @ AKTU | Backend Architecture & Full-Stack Development | Aspiring Python & Java Engineer
  ```
- **Social links on left sidebar:**
  Add `linkedin.com/in/prakhar300` and your email.
