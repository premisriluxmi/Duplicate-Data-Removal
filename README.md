# Duplicate Data Removal Using Pandas

A beginner-friendly Python project demonstrating how to identify and remove duplicate records using Pandas.

## Objective

To identify duplicate rows, remove them, and compare dataset sizes before and after cleaning.

## Technologies Used

- Python
- Pandas
- Jupyter Notebook

## Concepts Used

- `pd.DataFrame()` – creates a DataFrame
- `duplicated()` – identifies duplicate rows
- `drop_duplicates()` – removes duplicate rows
- `len()` – counts rows
- Data cleaning and verification

## Dataset

A manually created student dataset containing seven rows and three columns:

- Name
- Age
- Marks

The dataset intentionally includes duplicate records for demonstration.

## Results

| Measurement | Result |
|---|---:|
| Original Rows | 7 |
| Duplicate Rows Found | 2 |
| Rows After Cleaning | 5 |
| Rows Removed | 2 |
| Remaining Duplicate Rows | 0 |

## Explanation

The dataset was checked for duplicate records using Pandas `duplicated()`.

The `drop_duplicates()` function was then used to remove repeated rows while retaining their first occurrences.

The row counts before and after cleaning were compared, and the cleaned dataset was checked again to confirm that no duplicates remained.

## How to Run

1. Open `Duplicate_Data_Removal.ipynb` in VS Code or Jupyter Notebook.
2. Install Pandas if necessary using `pip install pandas`.
3. Select the Python kernel.
4. Run all cells from top to bottom.
5. Review the duplicate records and final report.

## Learning Outcome

- Learned to identify duplicate records using Pandas.
- Practiced removing duplicate rows.
- Compared dataset sizes before and after cleaning.
- Verified that duplicate rows were removed.
- Understood the importance of data cleaning before analysis and modeling.

## Project Structure

```text
Duplicate-Data-Removal/
│
├── Duplicate_Data_Removal.ipynb
└── README.md
```