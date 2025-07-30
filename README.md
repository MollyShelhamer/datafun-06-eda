# datafun-06-eda

## Project Overview

This project is part of the **CC6.1: Start a Python EDA Project** module. The goal is to set up a Python project that follows best practices for:

- Managing virtual environments
- Using GitHub for version control
- Preparing for exploratory data analysis (EDA) using essential data science tools

📄 **Project Specification**: [datafun-06-spec](https://github.com/denisecase/datafun-06-spec)

---

## Setup Instructions

### 1. Project Initialization

- Created a new GitHub repo: `datafun-06-eda`
- Cloned the repo locally into the `Documents` folder
- Opened the project folder in VS Code

### 2. .gitignore File

Added the following entries to `.gitignore` to prevent unnecessary files from being tracked:
- .vscode/
- .venv/
- .ipynb_checkpoints/
- pycache/

---

## Virtual Environment Setup

### 3. Create & Activate Virtual Environment

Open a terminal in VS Code:

```bash
# Pull latest changes from GitHub
git pull

# Create a virtual environment named .venv
py -m venv .venv

# Activate environment (Windows)
.venv\Scripts\activate

# Activate environment (Mac/Linux)
source .venv/bin/activate

---

### 4. Install Required Packages
- py -m pip install --upgrade pip
- py -m pip install jupyterlab numpy pandas pyarrow matplotlib seaborn

