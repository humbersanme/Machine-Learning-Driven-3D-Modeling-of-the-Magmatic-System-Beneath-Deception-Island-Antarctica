# Machine-Learning-Driven-3D-Modeling-of-the-Magmatic-System-Beneath-Deception-Island-Antarctica


# Geophysical Data Analysis: data_grad_etal_1997

This repository contains an initial exploratory analysis of a geophysical dataset from the Grad et al. (1997) study, focusing on gradient measurements and spatial coordinates.

## 📁 Dataset Description

The file `data_grad_etal_1997.csv` contains **132,248 records** with the following columns:

| Column | Description |
|--------|-------------|
| **V1, V2, V3** | Measurement values (possibly gradients or physical data). |
| **x_km, z_km** | Coordinates in kilometers. |
| **z_m** | Depth or elevation in meters. |
| **dist_profile** | Accumulated distance along the measured profile. |
| **x_real, y_real** | Real-world coordinates in a geographic or projected reference system. |

## 🧹 Data Cleaning

The following preprocessing steps were performed:

- Conversion of numeric columns to `float64` type
- Removal of duplicate rows
- Handling of missing values
- Data type verification and consistency checks

## 📈 Descriptive Statistics

A statistical summary of numeric variables is included, featuring:

- Mean, standard deviation, minimum, and maximum values
- Quartiles (25%, 50%, 75%)

## 🛠️ Technologies Used

- **Python 3**
- **Pandas** – Data manipulation and cleaning
- **Jupyter Notebook** – Interactive analysis

## 🚀 Usage

You can load and explore the data by running the `init_data_grad_1997.ipynb` notebook, which includes:

- CSV file loading
- Automated data cleaning
- Initial data preview
- Descriptive statistics

## 📌 Data Source

The data originates from the study:

**Grad et al. (1997)** – Geophysical gradient measurements and spatial coordinates.
