# How to Run the AHRI Health Informatics Assessment Project

This guide explains how to set up, run, and explore the results of **Simon Mufara’s AHRI Health Informatics Internship Assessment**.  
The project investigates **clinic attendance and hypertension patterns** using real-world datasets from rural KwaZulu-Natal (2018–2019).

---

## 1. Prerequisites

Before you begin, make sure you have:

- **Python 3.10+** installed → [Download Python](https://www.python.org/downloads/)
- **Git** installed → [Download Git](https://git-scm.com/downloads)
- **Visual Studio Code** (optional, but recommended)
- **Internet connection** (for package installation)

You can verify installations with:
```bash
python --version
git --version
## 2. Clone the Repository

First, clone this project to your local machine:

git clone https://github.com/Simon-Mufara/AHRI_Health_Informatics_Assessment.git
cd AHRI_Health_Informatics_Assessment


This will create a local folder containing all the project files.

## 3. Create a Virtual Environment

Set up an isolated Python environment for this project.

 On Windows:
python -m venv .venv
.venv\Scripts\activate

 On macOS/Linux:
python3 -m venv .venv
source .venv/bin/activate


When successful, your terminal should show something like:

(.venv) user@computer:~/AHRI_Health_Informatics_Assessment$

## 4. Install Required Packages

Once your virtual environment is active, install all dependencies:

pip install -r requirements.txt


This will install libraries like:

pandas – for data manipulation

numpy – for numerical analysis

matplotlib & seaborn – for static plots

plotly – for interactive visuals

jupyter – for running the notebook

## 5. Launch Jupyter Notebook

Start Jupyter Notebook inside Visual Studio Code or directly from your terminal.

Option 1: VS Code

Open the project folder in Visual Studio Code.

Install the Python and Jupyter extensions (if prompted).

Open the notebook:
notebooks/AHRI_Assessment.ipynb

Click "Run All" or Shift + Enter to execute each cell.

## Option 2: Command Line
jupyter notebook


Then open your web browser and click:

notebooks/AHRI_Assessment.ipynb

##  6. View Results and Figures

All generated graphs and charts will be automatically saved in the figures/ folder.

Example outputs include:

age_distribution.png

top_visit_reasons.png

hypertension_clinic_attendance.png

 You can also enable interactive Plotly visualizations by uncommenting the relevant code sections inside the notebook.

## 7. Cleaning and Resetting the Environment

To remove cached results and start fresh:

rm -rf figures/*


To deactivate your environment when done:

deactivate

## 8. Troubleshooting Tips
Issue	Cause	Solution
jupyter: command not found	Jupyter not installed	Run pip install jupyter
ModuleNotFoundError	Missing package	Run pip install -r requirements.txt again
PermissionError during setup	Windows path restriction	Run VS Code as Administrator
Plots not showing	Backend issue	Restart kernel and re-run notebook

## 9. Summary

By following these steps, you will:
 Set up a clean Python environment
 Run the AHRI analysis notebook
 View key visualizations and findings
 Reproduce Simon Mufara’s results locally

 ## Author

Simon Mufara
Bioinformatics Honours Student – University of Cape Town (2025)
Project: AHRI Health Informatics Internship Assessment
 November 2025
