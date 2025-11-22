# Imputation_Assignment
Titanic Dataset – Imputation Assignment
Assignment Goal

The goal of this assignment was to handle and fix missing values (NaN) in the Titanic dataset using different imputation techniques.

Work Done

Loaded the Titanic dataset from a public GitHub source using pandas.

Checked for missing values in all columns using isnull().sum().

Handled missing Age values using two imputation methods:

Median age based on Sex (male / female).

Median age based on Title extracted from the Name column (Mr, Miss, Mrs, Master, etc.).

Extracted the Title from each passenger’s Name using string operations.

Grouped rare titles such as Dr, Col, Rev, Countess, Major, Sir into a single category called “Rare”.

Used median Age for each Title to fill any remaining missing Age values.

Ensured all Age values were fully imputed and confirmed no missing Age entries remained.

Why Imputation Was Used

Missing values can cause problems in analysis and machine-learning models.

Imputation fills missing values with meaningful and realistic numbers.

Using Sex and Title makes the filled Age values more accurate because people with similar social titles usually fall within similar age ranges.
