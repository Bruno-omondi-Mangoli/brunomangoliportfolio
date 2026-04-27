# Bruno Omondi Mang'oli - Professional Portfolio

Welcome to the source code for Bruno Omondi Mang'oli's professional portfolio website. This project is a responsive, modern, and clean single-page application built with HTML, CSS, and JavaScript. It showcases Bruno's skills, experience, and featured projects including NyumbaHub, AccuLabel, and Kadimbotech Solutions.

## Features

- **Responsive Design:** Fully optimized for desktop, tablet, and mobile devices.
- **Modern UI/UX:** Clean typography, smooth scrolling, and subtle animations.
- **Project Showcase:** Dedicated sections for highlighting key web development and data annotation projects.
- **Contact Form:** A functional UI for a contact form (ready to be connected to a backend service like Formspree or Netlify Forms).

## Prerequisites

To run this project locally, you only need a modern web browser. However, for development purposes, it is recommended to use:

- [Git Bash](https://git-scm.com/downloads) (for running commands)
- [Visual Studio Code (VS Code)](https://code.visualstudio.com/) (for editing code)
- [Live Server Extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for VS Code (optional, but recommended for live reloading)

## How to Run Locally

Follow these steps to get the portfolio running on your local machine:

1. **Extract the Files:**
   Extract the downloaded `portfolio.zip` folder to a location on your computer (e.g., your Desktop or Documents folder).

2. **Open with VS Code:**
   - Open **Git Bash**.
   - Navigate to the extracted folder using the `cd` command. For example:
     ```bash
     cd ~/Desktop/portfolio
     ```
   - Open the folder in VS Code by typing:
     ```bash
     code .
     ```

3. **View the Website:**
   - **Method 1 (Simple):** Simply double-click the `index.html` file in your file explorer to open it in your default web browser.
   - **Method 2 (Recommended):** In VS Code, if you have the "Live Server" extension installed, right-click on `index.html` and select **"Open with Live Server"**. This will open the site in your browser and automatically refresh it whenever you save changes to the code.

## How to Deploy to GitHub and Make it Live (Production)

To make your portfolio accessible to the world, you can host it for free using **GitHub Pages**. Follow these steps:

### Step 1: Initialize Git and Commit Your Code

1. Open **Git Bash** and navigate to your project folder:
   ```bash
   cd path/to/your/portfolio
   ```
2. Initialize a new Git repository:
   ```bash
   git init
   ```
3. Add all your files to the staging area:
   ```bash
   git add .
   ```
4. Commit your changes:
   ```bash
   git commit -m "Initial commit: Add portfolio website files"
   ```

### Step 2: Create a GitHub Repository

1. Go to [GitHub](https://github.com/) and log in to your account (`Bruno-omondi-Mangoli`).
2. Click the **"+"** icon in the top right corner and select **"New repository"**.
3. Name your repository (e.g., `bruno-portfolio` or `Bruno-omondi-Mangoli.github.io`).
4. Make sure it is set to **Public**.
5. Do **not** initialize it with a README, .gitignore, or license (leave those unchecked).
6. Click **"Create repository"**.

### Step 3: Push Your Code to GitHub

1. On the next page, copy the commands under the section **"…or push an existing repository from the command line"**. It will look something like this:
   ```bash
   git remote add origin https://github.com/Bruno-omondi-Mangoli/your-repo-name.git
   git branch -M main
   git push -u origin main
   ```
2. Paste these commands into your **Git Bash** terminal and press Enter. (You may be prompted to authenticate with GitHub).

### Step 4: Enable GitHub Pages (Make it Live)

1. On your GitHub repository page, click on the **"Settings"** tab (the gear icon).
2. In the left sidebar, scroll down and click on **"Pages"**.
3. Under the **"Build and deployment"** section, look for **"Source"** and ensure it says "Deploy from a branch".
4. Under the **"Branch"** section, click the dropdown that says "None", select **`main`** (or `master`), and leave the folder as `/ (root)`.
5. Click **"Save"**.
6. Wait a minute or two, then refresh the page. You should see a message at the top saying: *"Your site is live at https://Bruno-omondi-Mangoli.github.io/your-repo-name/"*.
7. Click the link to view your live professional portfolio!

## Customization

- **Colors:** You can easily change the theme colors by modifying the CSS variables (`:root`) at the top of `assets/css/style.css`.
- **Content:** Update the text in `index.html` to reflect any new skills, experiences, or projects you acquire in the future.
- **Images:** Add your profile picture or project screenshots to the `assets/img/` folder and update the `src` attributes in the HTML.

---
*Built with ❤️ for Bruno Omondi Mang'oli.*
