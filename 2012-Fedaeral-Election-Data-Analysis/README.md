# 2012 Federal Election Commission Data Analysis

> 📊 A comprehensive exploratory data analysis of the 2012 Federal Election Commission (FEC) campaign finance data.

&#x20;

## ✨ Overview

This project analyzes the 2012 FEC campaign finance dataset to uncover trends in contributions, expenditures, and candidate funding sources. Through data cleaning, aggregation, and visualization, we aim to answer questions such as:

* Which top contributors and industries supported presidential and congressional campaigns?
* How did fundraising patterns differ across party lines and states?
* What are the spending categories and their relative proportions?

## 🛠️ Project Structure

```
├── 2012-Federal-Election-Commission-Data-Analysis.ipynb
├── requirements.txt                      # Python dependencies
└── README.md                             # Project overview and setup guide
```

## 📦 Prerequisites

* Python 3.8 or higher
* Jupyter Notebook or JupyterLab

You can check your Python version with:

```bash
python --version
```

## 🔧 Installation

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/2012-fec-data-analysis.git

````

2. **Create and activate a virtual environment**


3. **Install required packages**

```bash
pip install -r requirements.txt
````

## 🚀 Usage

1. **Prepare the data**  
   - Place the original `2012_full_campaign_data.csv` into `data/raw/`.
   - Run the cleaning script (if available) or load the raw CSV directly in the notebook.

2. **Launch Jupyter Notebook**

```bash
jupyter notebook notebooks/2012-Federal-Election-Commission-Data-Analysis.ipynb
````

3. **Explore the analysis**

   * Follow the notebook step-by-step to see data loading, cleaning, and visualization.
   * Cells are organized by sections: Data Loading, Cleaning & Transformation, Aggregations, and Visualizations.

## ⚙️ Key Dependencies

* `pandas` — data manipulation and aggregation
* `numpy` — numerical operations
* `matplotlib` — plotting library
* `seaborn` — statistical data visualization

You can install them via the `requirements.txt`:

```
pandas
numpy
matplotlib
seaborn
```

## 📜 License
```
This project is licensed under the MIT License.
```

> Created with ❤️ by Apabrita Maity
