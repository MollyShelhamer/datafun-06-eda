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

- Created a new GitHub repository named `datafun-06-eda`
- Cloned the repository locally into the `Documents` folder
- Opened the project folder in VS Code

### 2. .gitignore File

Added the following entries to `.gitignore`:

```
.vscode/
.venv/
.ipynb_checkpoints/
__pycache__/
```

---

## Virtual Environment Setup

### 3. Create & Activate Virtual Environment

Open a terminal in VS Code and run:

```bash
# Pull latest changes
git pull

# Create a virtual environment
py -m venv .venv

# Activate on Windows
.venv\Scripts\activate

# Activate on Mac/Linux
source .venv/bin/activate
```

### 4. Install Required Packages

```bash
py -m pip install --upgrade pip
py -m pip install jupyterlab numpy pandas pyarrow matplotlib seaborn
```

---

## VS Code Configuration

- Set the Python interpreter to use the `.venv` environment
- Verified that packages are accessible and JupyterLab runs correctly

---

## Version Control Commands

```bash
git add .
git commit -m "Initial project setup with virtual environment and required packages"
git push -u origin main
```

---

## Notes

- This setup ensures a clean, isolated development environment
- Jupyter notebooks are used for EDA and should be saved in the project folder
- Notebook checkpoints and environment-specific files are excluded from version control


