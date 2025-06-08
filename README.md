# data-mining-project-2025

This repository showcases a complete data mining workflow. The project was originally created for the 2024 course curriculum and demonstrates an end-to-end machine learning pipeline. All experiments are contained in a single Jupyter notebook and the raw data is provided as a CSV file.

## Objectives
- Build a supervised classification pipeline (preprocessing, feature engineering, model selection, and evaluation).
- Perform unsupervised analysis for clustering and anomaly detection.

## Dataset
The data comes from [info.data.gov.il](https://info.data.gov.il/) and includes bond issuance information such as coupon rates, purchase quantities, and maturity dates. It is stored in `bonds.csv` in this repository.

Key columns include:
- **BONDS** – bond type (classification target).
- **COUPON** – coupon rate.
- **PURCHASEDQUANTITY** – quantity purchased.
- **AVERAGEPRICE** and **CUTOFFPRICE** – pricing information.
- **ACTUALTERMTOMATURITY** – time to maturity.

## Usage
Install the packages listed in `requirements.txt` and open the notebook `Data Mining Supervised & Unsupervised 2025.ipynb` to run the analysis:
```bash
pip install -r requirements.txt
jupyter notebook Data\ Mining\ Supervised\ \&\ Unsupervised\ 2025.ipynb
```

## Repository Structure
- `bonds.csv` – raw dataset used in the notebook.
- `Data Mining Supervised & Unsupervised 2025.ipynb` – Jupyter notebook containing all code and analysis.
- `requirements.txt` – list of Python packages required to run the notebook.

