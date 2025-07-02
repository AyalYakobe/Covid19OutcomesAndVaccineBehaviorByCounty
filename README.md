# Covid19OutcomesAndVaccineBehaviorByCounty

## Project Overview

Political divisions in the U.S. have influenced public attitudes toward COVID-19, including risk perception, mitigation compliance, and vaccination behavior. This project investigates how political alignment correlates with COVID-19-related outcomes—such as infection rates, mortality, vaccine hesitancy, and uptake—across U.S. counties from 2020 to 2024.

Using structural and demographic predictors (e.g., social vulnerability, healthcare burden, poverty, population density), we explore both supervised and unsupervised learning approaches to analyze these patterns. While political partisanship plays a role, we find that structural context and intensity of alignment offer deeper explanatory power than party affiliation alone.

## Notebooks Included

- `Copy of STATS-4241-P1.ipynb` – Data cleaning, preprocessing, and unsupervised learning (PCA, clustering).
- `Copy of STATS-4241-P2.ipynb` – Supervised learning (classification, regression, model evaluation).

## How to Run

### Option 1: Recommended (Google Colab)
1. Open the notebooks directly in Google Colab using the links provided in this repo.
2. All datasets are accessible via the following Google Drive folder:  
   [STATS-4241 Google Drive](https://drive.google.com/drive/folders/18C_1ySJlDdzOYVdi1PIUqRUfJzhhOmNr?usp=sharing)
3. You may need to **change file paths** to match your Google Drive mount directory in Colab (e.g., `/content/drive/MyDrive/STATS-4241/...`).

### Option 2: Local (Not Recommended)
1. Clone or download this GitHub repository.
2. Download all datasets from the Google Drive folder linked above or simply download the STATS-4241 folder above.
3. Update file paths in the notebooks to point to your local data files.
4. Run the notebooks using Jupyter or VS Code with a Python environment that includes required libraries (e.g., pandas, scikit-learn, matplotlib, seaborn).

## Folder Structure

