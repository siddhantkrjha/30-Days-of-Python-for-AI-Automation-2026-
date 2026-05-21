# GitHub Account Security Setup Guide

Before working with course projects, secure your GitHub account properly.

This protects your code, repositories, and future portfolio projects.

---

# Step 1: Create a GitHub Account

Visit:

https://github.com

Create a personal account using:

- professional username
- active email address
- strong password

Avoid using:

- nicknames
- gaming usernames
- temporary email accounts

Your GitHub profile becomes part of your professional portfolio.

---

# Step 2: Enable Two-Factor Authentication (2FA)

Navigate to:

Settings → Password and Authentication

Enable:

✓ Two-Factor Authentication

Recommended methods:

1. Authenticator App
2. Security Key

Avoid relying solely on SMS when possible.

Benefits:

- protects account access
- prevents unauthorized logins
- secures repositories

---

# Step 3: Verify Email Address

Navigate to:

Settings → Emails

Confirm your email address.

Benefits:

- password recovery
- commit verification
- account security notifications

---

# Step 4: Create SSH Authentication (Recommended)

Open terminal:

Windows:
PowerShell

Mac/Linux:
Terminal

Generate SSH key:

ssh-keygen -t ed25519 -C "your_email@example.com"

Add public key to:

GitHub → Settings → SSH and GPG Keys

Benefits:

- secure authentication
- avoids repeated password prompts
- professional workflow

---

# Step 5: Install Visual Studio Code

Download:

https://code.visualstudio.com

Install:

- Python Extension
- GitHub Pull Requests Extension
- GitHub Copilot (optional)

VS Code is the primary development environment used throughout this course.

---

# Step 6: Clone the Course Repository

Example:

git clone https://github.com/your-course-repository.git

Open:

File → Open Folder

Select repository folder.

You can now work locally without modifying the official repository.

---

# Step 7: Create Your Own Portfolio Repository

Recommended naming:

python-automation-portfolio

Store:

- projects
- exercises
- automation tools
- dashboards
- AI applications

This repository will become part of your professional portfolio.

---

# Step 8: Never Upload Secrets

Never commit:

- passwords
- API keys
- tokens
- private credentials
- database passwords

Use:

.env files

Example:

OPENAI_API_KEY=your_key_here

Never upload real credentials to GitHub.

---

# Step 9: Keep Dependencies Updated

Periodically update:

- Python packages
- VS Code extensions
- Git tools

This improves security and stability.

---

# Recommended Student Workflow

1. Clone course repository
2. Open in VS Code
3. Complete exercises
4. Build your own project variation
5. Commit work locally
6. Push to personal GitHub portfolio
7. Continue improving projects

Learning happens when you build, modify, and experiment with code yourself.

Use the course repository as a foundation, then create projects that demonstrate your own problem-solving skills.
