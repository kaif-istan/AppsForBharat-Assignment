# Store & SKU Conversion Analysis Project

## 📌 Project Overview
This repository contains a comprehensive analysis of store and SKU-level conversion rates for a retail business, including:
- Python data analysis in Jupyter Notebook
- LaTeX report generation
- Visualization of key metrics

## 🛠️ Technical Stack
- **Python 3.8+** (Pandas, Matplotlib, Seaborn)
- **Jupyter Notebook** for interactive analysis
- **LaTeX** for professional report generation
- **Git/GitHub** for version control

## 📂 Repository Structure

    /AppsForBharat-Assignment/
│
├── /data/ # Raw and processed data files
│ ├── store_sku_ba_dataset.csv # Original dataset
│ ├── store_conversion_rates.csv # Processed store metrics
│ └── sku_conversion_rates.csv # Processed SKU metrics
│
├── /notebooks/ # Jupyter notebooks
│ └── conversion_analysis.ipynb # Main analysis notebook
│
├── /reports/ # Generated outputs
│ ├── analysis_report.pdf # 3-page PDF report
│ └── visuals/ # Plot images
│ ├── store_conversion_distribution.png
│ ├── sku_conversion_distribution.png
│ └── revenue_vs_conversion.png
│
├── /latex/ # LaTeX source files
│ └── report_template.tex # Condensed 3-page template
│
└── README.md


## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Lab/Notebook
- LaTeX distribution (TeX Live/MikTeX)
- Git

### Installation
```bash
git clone https://github.com/yourusername/store-sku-analysis.git
cd store-sku-analysis

# Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

# Install requirements
pip install -r requirements.txt


### 🔍 Analysis Approach
# Data Preparation

Load and clean transaction data

Calculate conversion rates (Transactions/Visits)

# Performance Analysis

Identify top/bottom performing stores and SKUs

Analyze revenue-conversion relationships

# Visualization

Generate distribution plots

Create scatter plots for revenue vs. conversion

# Reporting

Export key metrics to CSV

Generate 3-page PDF report with LaTeX

### 🏗️ How to Reproduce Results
# Run the Jupyter notebook:

```bash
jupyter notebook notebooks/conversion_analysis.ipynb

# Generate PDF report:
```bash
pdflatex latex/report_template.tex -output-directory=reports/