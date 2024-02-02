**# Rsync Deployment Code Sample**

**## Introduction**

This repository provides a simple rsync/ssh deployment code sample for your projects. By following these steps, you can easily set up manual deployments using GitHub Actions.

**### Instructions**

1. **GitHub Repository Setup:**
   - Navigate to your GitHub repository.
   - Click on "Settings" in the top menu.

2. **Secrets and Variables Setup:**
   - In the sidebar, select "Secrets and variables."
   - Click on the "Actions" tab.
   - Create the following secrets and enter your credentials:
      - `ssh_host` (Copy and paste the name from here.)
      - `ssh_username`
      - `ssh_port`
      - `ssh_private_key` (Ensure you create public/private keys without a password.)



**## Manual Deployment**

To perform a manual deployment, follow these steps:

1. **GitHub Actions:**
   - Visit the "ACTIONS" tab in your repository.

2. **Choose Deployment:**
   - Locate the deployment named "PROJECT-NAME DEPLOYMENT - PRODUCTION."

3. **Run Workflow:**
   - Click on the "RUN WORKFLOW" button.
   - In the drop-down select menu, choose the branch you wish to deploy.

4. **Initiate Deployment:**
   - Click on the green "RUN WORKFLOW" button.

5. **Wait for Deployment:**
   - Allow some time for the deployment process to initiate.


Feel free to customize and use this code according to your project's needs.
