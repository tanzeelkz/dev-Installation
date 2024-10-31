Jenkins Installation Setup

This document provides a step-by-step guide for installing Jenkins on a Debian-based Linux system (e.g., Ubuntu). This guide will walk you through the installation process.

Prerequisites
- A Debian-based Linux system (e.g., Ubuntu).
- sudo privileges to install software.

Step-by-Step Installation

Step 1: Clone the Repository
1. Open your terminal.
2. Clone this repository to your local machine using the following command:
   ```bash
   git clone https://github.com/username/jenkins-setup.git
   ```
   Replace `username` with your GitHub username.
3. Navigate to the cloned directory:
   ```bash
   cd jenkins-setup
   ```

Step 2: Make the Installation Script Executable
Before running the installation script, you need to make it executable:
```bash
chmod +x install-jenkins.sh
```

Step 3: Run the Installation Script
Now, run the installation script to install Jenkins:
```bash
./install-jenkins.sh
```

Step 4: Access Jenkins
1. Once the installation is complete, open your web browser.
2. Go to the following URL to access Jenkins:
   ```
   http://localhost:8080
   ```

Step 5: Retrieve the Initial Admin Password
To set up Jenkins, you'll need the initial admin password. This password is generated during the installation process and can be found in the terminal output or directly from the file:
```bash
cat /var/lib/jenkins/secrets/initialAdminPassword
```
