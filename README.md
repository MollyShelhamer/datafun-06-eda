# datafun-06-eda

## Project Overview

The goal is to set up a Python project that follows best practices for:

- Managing virtual environments  
- Using GitHub for version control  
- Preparing for exploratory data analysis (EDA)

## 🐧 Penguins Dataset

This project uses the **Penguins** dataset from the [Seaborn data repository](https://github.com/mwaskom/seaborn-data/blob/master/penguins.csv), a modern alternative to the classic Iris dataset for classification tasks. It contains measurements of penguins from three different species collected from the Palmer Archipelago in Antarctica.

The dataset includes **344** observations with both numerical and categorical variables that are useful for data visualization, statistical modeling, and machine learning.

### 🔍 Dataset Summary

| Column           | Type      | Description                                                  |
|------------------|-----------|--------------------------------------------------------------|
| `species`        | category  | Penguin species (`Adelie`, `Chinstrap`, `Gentoo`)           |
| `island`         | category  | Island where the penguin was observed (`Biscoe`, `Dream`, `Torgersen`) |
| `bill_length_mm` | float     | Length of the penguin's bill (in millimeters)               |
| `bill_depth_mm`  | float     | Depth of the penguin's bill (in millimeters)                |
| `flipper_length_mm` | float  | Length of the penguin's flipper (in millimeters)            |
| `body_mass_g`    | float     | Body mass (in grams)                                        |
| `sex`            | category  | Sex of the penguin (`Male`, `Female`)                       |
| `year`           | integer   | Year the observation was made                               |

> 🛠️ **Note:** Some rows contain missing values (e.g., in `sex` and body measurements), which may require handling during preprocessing.

### 💡 Use Cases

This dataset is ideal for:

- Classification (e.g., predicting species based on physical characteristics)
- Data cleaning and preprocessing demonstrations
- Exploratory data analysis and plotting practice
- Examples of handling missing data and categorical variables

### 📄 License

The dataset is made available under the [BSD license](https://github.com/mwaskom/seaborn-data/blob/master/LICENSE) and is free to use for educational and research purposes.


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


