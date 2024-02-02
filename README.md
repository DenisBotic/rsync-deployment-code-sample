**# Rsync Deployment Code Sample**
<br><br>

**## Introduction**
<br>
This repository provides a simple rsync/ssh deployment code sample for your projects. By following these steps, you can easily set up manual deployments using GitHub Actions.
<br><br>

**### Instructions**
<br>
1. **GitHub Repository Setup:**
   - Navigate to your GitHub repository.
   - Click on "Settings" in the top menu.
<br>
2. **Secrets and Variables Setup:**
   - In the sidebar, select "Secrets and variables."
   - Click on the "Actions" tab.
   - Create the following secrets and enter your credentials:
      - `ssh_host` (Copy and paste the name from here.)
      - `ssh_username`
      - `ssh_port`
      - `ssh_private_key` (Ensure you create public/private keys without a password.)
<br><br><br>


**## Manual Deployment**
<br>
To perform a manual deployment, follow these steps:
<br>
1. **GitHub Actions:**
   - Visit the "ACTIONS" tab in your repository.
<br>
2. **Choose Deployment:**
   - Locate the deployment named "PROJECT-NAME DEPLOYMENT - PRODUCTION."
<br>
3. **Run Workflow:**
   - Click on the "RUN WORKFLOW" button.
   - In the drop-down select menu, choose the branch you wish to deploy.
<br>
4. **Initiate Deployment:**
   - Click on the green "RUN WORKFLOW" button.
<br>
5. **Wait for Deployment:**
   - Allow some time for the deployment process to initiate.
<br><br>

Feel free to customize and use this code according to your project's needs.
