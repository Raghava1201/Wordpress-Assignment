# WordPress Deployment using GitHub Actions

## 📌 Project Overview
This project demonstrates how to manually set up and deploy a WordPress website using **GitHub Actions**. The repository includes a GitHub Actions workflow that automates the deployment process.

---

## 🔧 Step 1: Setting Up the Repository
1. **Created a new GitHub repository** named `Wordpress-Assignment`.
2. **Initialized the repository** and added necessary files.
3. **Cloned the repository locally** using:
   git clone https://github.com/Raghava1201/Wordpress-Assignment.git
   cd Wordpress-Assignment
---
## Step 2: Setting Up WordPress Manually
1.Downloaded WordPress from the official website:
https://wordpress.org/download/
2.Extracted WordPress files and moved them to the project directory.
3.Configured the database:
     Created a MySQL database.
     Created a database user and granted permissions.
4.Updated wp-config.php with database details.
5.Started a local server (Apache or Nginx) and placed WordPress files in the web directory.

---
## ⚙ Step 3: Creating the GitHub Actions Workflow
1.Created a .github/workflows/deploy.yml file to automate the deployment process.
2.Configured the workflow to:
     Trigger on push to the main branch.
     Deploy WordPress automatically.
3.Committed and pushed the workflow file
    ( git add .github/workflows/deploy.yml
     git commit -m "Added deploy.yml file"
     git push origin main )
4.Verified the workflow run in GitHub Actions (Success ✅).

---
## 🚀 Step 4: Deploying the Website Using GitHub Actions
1.Pushed changes to the main branch, which automatically triggered the workflow.
2.Checked GitHub Actions (Actions tab in the repository) to ensure deployment was successful.
3.Deployment status: ✅ Successful.

---
## 📋 Requirements
1.A web server (Apache/Nginx)
2.PHP and MySQL installed
3.GitHub Actions configured for automated deployment
4.A hosting platform/server for deployment

## Step by Step process is updated in this github repo --> document.docx

