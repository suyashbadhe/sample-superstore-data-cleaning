# Sample Superstore – Data Cleaning Using Python

## About this project

This is my first hands-on data analytics project. I used the Sample Superstore dataset to practise data cleaning and basic data validation using Python and Pandas in Google Colab.

The dataset initially contained 10,194 rows and 21 columns. My aim was to understand the data, check its quality, identify unusual values, and prepare it for further analysis.

## Tools Used

- Python
- Pandas
- Google Colab

## Work I Completed

Here are the main tasks I performed:

1. Loaded the dataset and inspected its rows, columns and data types.
2. Checked for missing values.
3. Checked for duplicate records.
4. Validated sales, quantity and date columns.
5. Checked customer and product identifiers.
6. Investigated unusually high discounts.
7. Analysed records with negative profit.
8. Created a new column called `Shipping_Days` using the order and shipping dates.
9. Performed final data quality checks.

## Some Results

- Total records reviewed: 10,194
- Missing values: 0
- Exact duplicate rows: 0
- Invalid sales records: 0
- Invalid quantity records: 0
- Shipping dates earlier than order dates: 0
- Negative-profit records identified: 1,901

## What I Learned

One thing I learned during this project is that unusual values are not always incorrect values.

For example, I found records with negative profit. Instead of deleting them, I kept them because they could represent actual business losses in the sample data.

I also learned why it is important to check data carefully before starting analysis.

## Repository Structure

```text
sample-superstore-data-cleaning/
│
├── README.md
├── notebooks/
│   └── Superstore_Data_Cleaning.ipynb
├── outputs/
│   ├── README.md
│   ├── missing_values.png
│   ├── data_quality_checks.png
│   └── final_validation.png
└── data/
    └── README.md
```

## How to View This Project

1. Open the notebook inside the `notebooks` folder.
2. Review the Python code and its outputs.
3. Check the `outputs` folder to see screenshots of the data quality checks.

The dataset is not included in this repository. Please obtain a copy of the Sample Superstore practice dataset to run the notebook.
