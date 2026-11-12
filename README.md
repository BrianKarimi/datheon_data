# Exploratory Data Analysis of Superstore Retail Sales

## 1. Project Overview

This project conducts an exploratory data analysis (EDA) of a Superstore retail sales dataset to examine commercial performance and identify patterns in customer purchasing behaviour, product sales, profitability and regional distribution.

The analysis uses Python-based data analytics techniques to inspect, clean and transform transactional data in preparation for commercial analysis and business intelligence reporting.

The project aims to translate raw retail transaction records into meaningful business insights that can support evidence-based decision-making.

## 2. Project Objectives

The specific objectives are to:

1. Assess the structure, completeness and quality of the retail sales dataset.
2. Perform data cleaning, transformation and preparation using Python.
3. Analyse customer purchasing activity and sales performance.
4. Examine revenue and profitability across product categories, regions and customer segments.
5. Investigate monthly sales trends and seasonal patterns.
6. Examine the relationship between discount levels and profitability.
7. Develop evidence-based business findings and recommendations.

## 3. Dataset Description

The project uses the Superstore Retail Sales dataset obtained from Datheon's internship dataset repository.

**Dataset source:** [Download Superstore Sales Dataset](https://www.datheon.in/datasets/superstore_sales.csv)

The original CSV file contains 10,800 rows and 21 columns. These records include transactional information relating to:

- Order and shipping dates.
- Customer identification and segmentation.
- Geographic information.
- Product categories and sub-categories.
- Sales, quantities, discounts and profits.

The dataset covers transactions recorded between 3 January 2015 and 30 December 2018.

## 4. Tools and Technologies

The following tools and libraries are used in this project:

| Tool / Library | Application |
|---|---|
| Python | Data analysis and processing |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Seaborn | Statistical visualisation |
| Jupyter Notebook | Interactive analysis and documentation |
| VS Code | Development environment |
| GitHub | Version control and project documentation |

## 5. Repository Structure

```text
superstore-eda/
│
├── # Exploratory Data Analysis of Superstore Retail Sales

## 1. Project Overview

This project conducts an exploratory data analysis (EDA) of a Superstore retail sales dataset to examine commercial performance and identify patterns in customer purchasing behaviour, product sales, profitability and regional distribution.

The analysis uses Python-based data analytics techniques to inspect, clean and transform transactional data in preparation for commercial analysis and business intelligence reporting.

The project aims to translate raw retail transaction records into meaningful business insights that can support evidence-based decision-making.

## 2. Project Objectives

The specific objectives are to:

1. Assess the structure, completeness and quality of the retail sales dataset.
2. Perform data cleaning, transformation and preparation using Python.
3. Analyse customer purchasing activity and sales performance.
4. Examine revenue and profitability across product categories, regions and customer segments.
5. Investigate monthly sales trends and seasonal patterns.
6. Examine the relationship between discount levels and profitability.
7. Develop evidence-based business findings and recommendations.

## 3. Dataset Description

The project uses the Superstore Retail Sales dataset obtained from Datheon's internship dataset repository.

**Dataset source:** [Download Superstore Sales Dataset](https://www.datheon.in/datasets/superstore_sales.csv)

The original CSV file contains 10,800 rows and 21 columns. These records include transactional information relating to:

- Order and shipping dates.
- Customer identification and segmentation.
- Geographic information.
- Product categories and sub-categories.
- Sales, quantities, discounts and profits.

The dataset covers transactions recorded between 3 January 2015 and 30 December 2018.

## 4. Tools and Technologies

The following tools and libraries are used in this project:

| Tool / Library | Application |
|---|---|
| Python | Data analysis and processing |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Seaborn | Statistical visualisation |
| Jupyter Notebook | Interactive analysis and documentation |
| VS Code | Development environment |
| GitHub | Version control and project documentation |

## 5. Repository Structure

```text
superstore-eda/
│
├── data/
│   ├── superstore_sales.csv
│   └── superstore_cleaned.csv
│
├── notebooks/
│   └── superstore_eda.ipynb
│
├── outputs/
│   ├── figures/
│   └── reports/
│
├── README.md
└── requirements.txt
```

## 6. Data Cleaning and Preparation

The initial dataset inspection identified additional records that did not conform to the main transactional structure.

The cleaning process involved:

- Excluding 806 non-transactional or appended records from the analytical dataset.
- Retaining 9,994 valid transaction records.
- Converting `Order Date` and `Ship Date` into datetime formats.
- Converting relevant numerical variables into appropriate numeric data types.
- Extracting `Order Year`, `Order Month` and `Year-Month` from the order date.
- Checking for duplicate transaction records.
- Profiling missing values.

The original dataset was preserved, and the cleaned dataset was saved separately as `superstore_cleaned.csv`.

## 7. Initial Data Quality Assessment

The initial assessment produced the following results:

| Data Quality Indicator | Result |
|---|---:|
| Original records | 10,800 |
| Valid transaction records | 9,994 |
| Excluded records | 806 |
| Original variables | 21 |
| Variables after transformation | 24 |
| Exact duplicate records | 0 |
| Missing postal codes | 11 |
| Missing order dates | 0 |
| Missing sales values | 0 |

The 11 missing postal codes were retained rather than deleting the associated transactions, as postal codes are not essential to the planned commercial analysis.

The cleaned dataset contains 9,994 records and 24 variables.

## 8. Project Progress

The project is being developed in stages.

| Activity | Status |
|---|---|
| Dataset acquisition | Completed |
| Initial dataset inspection | Completed |
| Missing-value profiling | Completed |
| Identification of appended records | Completed |
| Removal of non-transactional records | Completed |
| Date parsing and transformation | Completed |
| Creation of Year-Month variable | Completed |
| Initial duplicate assessment | Completed |
| Additional numerical and date validation | In progress |
| Customer purchasing analysis | Pending |
| Category-wise sales and profit analysis | Pending |
| Regional performance analysis | Pending |
| Customer segment analysis | Pending |
| Monthly sales trend analysis | Pending |
| Discount sensitivity analysis | Pending |
| Executive findings and recommendations | Pending |

## 9. Reproducibility and Installation

To reproduce the analysis:

**Step 1: Clone the repository**

```bash
git clone <your-github-repository-url>
cd superstore-eda
```

**Step 2: Create a virtual environment**

```bash
python -m venv .venv
```

**Step 3: Activate the environment (Windows)**

```bash
.venv\Scripts\activate
```

**Step 4: Install dependencies**

```bash
pip install -r requirements.txt
```

**Step 5: Launch Jupyter Notebook**
# Exploratory Data Analysis of Superstore Retail Sales

## 1. Project Overview

This project conducts an exploratory data analysis (EDA) of a Superstore retail sales dataset to examine commercial performance and identify patterns in customer purchasing behaviour, product sales, profitability and regional distribution.

The analysis uses Python-based data analytics techniques to inspect, clean and transform transactional data in preparation for commercial analysis and business intelligence reporting.

The project aims to translate raw retail transaction records into meaningful business insights that can support evidence-based decision-making.

## 2. Project Objectives

The specific objectives are to:

1. Assess the structure, completeness and quality of the retail sales dataset.
2. Perform data cleaning, transformation and preparation using Python.
3. Analyse customer purchasing activity and sales performance.
4. Examine revenue and profitability across product categories, regions and customer segments.
5. Investigate monthly sales trends and seasonal patterns.
6. Examine the relationship between discount levels and profitability.
7. Develop evidence-based business findings and recommendations.

## 3. Dataset Description

The project uses the Superstore Retail Sales dataset obtained from Datheon's internship dataset repository.

**Dataset source:** [Download Superstore Sales Dataset](https://www.datheon.in/datasets/superstore_sales.csv)

The original CSV file contains 10,800 rows and 21 columns. These records include transactional information relating to:

- Order and shipping dates.
- Customer identification and segmentation.
- Geographic information.
- Product categories and sub-categories.
- Sales, quantities, discounts and profits.

The dataset covers transactions recorded between 3 January 2015 and 30 December 2018.

## 4. Tools and Technologies

The following tools and libraries are used in this project:

| Tool / Library | Application |
|---|---|
| Python | Data analysis and processing |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Seaborn | Statistical visualisation |
| Jupyter Notebook | Interactive analysis and documentation |
| VS Code | Development environment |
| GitHub | Version control and project documentation |

## 5. Repository Structure

```text
superstore-eda/
│
├── data/
│   ├── superstore_sales.csv
│   └── superstore_cleaned.csv
│
├── notebooks/
│   └── superstore_eda.ipynb
│
├── outputs/
│   ├── figures/
│   └── reports/
│
├── README.md
└── requirements.txt
```

## 6. Data Cleaning and Preparation

The initial dataset inspection identified additional records that did not conform to the main transactional structure.

The cleaning process involved:

- Excluding 806 non-transactional or appended records from the analytical dataset.
- Retaining 9,994 valid transaction records.
- Converting `Order Date` and `Ship Date` into datetime formats.
- Converting relevant numerical variables into appropriate numeric data types.
- Extracting `Order Year`, `Order Month` and `Year-Month` from the order date.
- Checking for duplicate transaction records.
- Profiling missing values.

The original dataset was preserved, and the cleaned dataset was saved separately as `superstore_cleaned.csv`.

## 7. Initial Data Quality Assessment

The initial assessment produced the following results:

| Data Quality Indicator | Result |
|---|---:|
| Original records | 10,800 |
| Valid transaction records | 9,994 |
| Excluded records | 806 |
| Original variables | 21 |
| Variables after transformation | 24 |
| Exact duplicate records | 0 |
| Missing postal codes | 11 |
| Missing order dates | 0 |
| Missing sales values | 0 |

The 11 missing postal codes were retained rather than deleting the associated transactions, as postal codes are not essential to the planned commercial analysis.

The cleaned dataset contains 9,994 records and 24 variables.

## 8. Project Progress

The project is being developed in stages.

| Activity | Status |
|---|---|
| Dataset acquisition | Completed |
| Initial dataset inspection | Completed |
| Missing-value profiling | Completed |
| Identification of appended records | Completed |
| Removal of non-transactional records | Completed |
| Date parsing and transformation | Completed |
| Creation of Year-Month variable | Completed |
| Initial duplicate assessment | Completed |
| Additional numerical and date validation | In progress |
| Customer purchasing analysis | Pending |
| Category-wise sales and profit analysis | Pending |
| Regional performance analysis | Pending |
| Customer segment analysis | Pending |
| Monthly sales trend analysis | Pending |
| Discount sensitivity analysis | Pending |
| Executive findings and recommendations | Pending |

## 9. Reproducibility and Installation

To reproduce the analysis:

**Step 1: Clone the repository**

```bash
git clone <your-github-repository-url>
cd superstore-eda
```

**Step 2: Create a virtual environment**

```bash
python -m venv .venv
```

**Step 3: Activate the environment (Windows)**

```bash
.venv\Scripts\activate
```

**Step 4: Install dependencies**

```bash
pip install -r requirements.txt
```

**Step 5: Launch Jupyter Notebook**

```bash
jupyter notebook
```

Open `notebooks/superstore_eda.ipynb` and execute the analysis cells.

Ensure that the dataset is available in the `data/` directory.

## 10. Expected Deliverables

Upon completion, the project will include:

- A documented and reproducible Jupyter Notebook.
- A cleaned and validated retail sales dataset.
- Exploratory analysis and descriptive statistics.
- Visualisations of customer, product, regional and monthly sales performance.
- Discount and profitability analysis.
- At least five evidence-based executive findings.
- Practical business recommendations.

---

**Project:** Exploratory Data Analysis on Superstore Retail Sales  
**Development Environment:** Python / Jupyter Notebook / VS Code  
**Project Status:** Work in Progress
```bash
jupyter notebook
```

Open `notebooks/superstore_eda.ipynb` and execute the analysis cells.

Ensure that the dataset is available in the `data/` directory.

## 10. Expected Deliverables

Upon completion, the project will include:

- A documented and reproducible Jupyter Notebook.
- A cleaned and validated retail sales dataset.
- Exploratory analysis and descriptive statistics.
- Visualisations of customer, product, regional and monthly sales performance.
- Discount and profitability analysis.
- At least five evidence-based executive findings.
- Practical business recommendations.

---

**Project:** Exploratory Data Analysis on Superstore Retail Sales  
**Development Environment:** Python / Jupyter Notebook / VS Code  
**Project Status:** Work in Progress├── superstore_sales.csv
│   └── superstore_cleaned.csv
│
├── notebooks/
│   └── superstore_eda.ipynb
│
├── outputs/
│   ├── figures/
│   └── reports/
│
├── README.md
└── requirements.txt
```

## 6. Data Cleaning and Preparation

The initial dataset inspection identified additional records that did not conform to the main transactional structure.

The cleaning process involved:

- Excluding 806 non-transactional or appended records from the analytical dataset.
- Retaining 9,994 valid transaction records.
- Converting `Order Date` and `Ship Date` into datetime formats.
- Converting relevant numerical variables into appropriate numeric data types.
- Extracting `Order Year`, `Order Month` and `Year-Month` from the order date.
- Checking for duplicate transaction records.
- Profiling missing values.

The original dataset was preserved, and the cleaned dataset was saved separately as `superstore_cleaned.csv`.

## 7. Initial Data Quality Assessment

The initial assessment produced the following results:

| Data Quality Indicator | Result |
|---|---:|
| Original records | 10,800 |
| Valid transaction records | 9,994 |
| Excluded records | 806 |
| Original variables | 21 |
| Variables after transformation | 24 |
| Exact duplicate records | 0 |
| Missing postal codes | 11 |
| Missing order dates | 0 |
| Missing sales values | 0 |

The 11 missing postal codes were retained rather than deleting the associated transactions, as postal codes are not essential to the planned commercial analysis.

The cleaned dataset contains 9,994 records and 24 variables.

## 8. Project Progress

The project is being developed in stages.

| Activity | Status |
|---|---|
| Dataset acquisition | Completed |
| Initial dataset inspection | Completed |
| Missing-value profiling | Completed |
| Identification of appended records | Completed |
| Removal of non-transactional records | Completed |
| Date parsing and transformation | Completed |
| Creation of Year-Month variable | Completed |
| Initial duplicate assessment | Completed |
| Additional numerical and date validation | In progress |
| Customer purchasing analysis | Pending |
| Category-wise sales and profit analysis | Pending |
| Regional performance analysis | Pending |
| Customer segment analysis | Pending |
| Monthly sales trend analysis | Pending |
| Discount sensitivity analysis | Pending |
| Executive findings and recommendations | Pending |

## 9. Reproducibility and Installation

To reproduce the analysis:

**Step 1: Clone the repository**

```bash
git clone <your-github-repository-url>
cd superstore-eda
```

**Step 2: Create a virtual environment**

```bash
python -m venv .venv
```

**Step 3: Activate the environment (Windows)**

```bash
.venv\Scripts\activate
```

**Step 4: Install dependencies**

```bash
pip install -r requirements.txt
```

**Step 5: Launch Jupyter Notebook**

```bash
jupyter notebook
```

Open `notebooks/superstore_eda.ipynb` and execute the analysis cells.

Ensure that the dataset is available in the `data/` directory.

## 10. Expected Deliverables

Upon completion, the project will include:

- A documented and reproducible Jupyter Notebook.
- A cleaned and validated retail sales dataset.
- Exploratory analysis and descriptive statistics.
- Visualisations of customer, product, regional and monthly sales performance.
- Discount and profitability analysis.
- At least five evidence-based executive findings.
- Practical business recommendations.
