#  Air Quality Data Analysis Using Python

## Project Overview

This project analyzes the **Air Quality dataset** using Python and Pandas. The purpose of the assignment is to practice fundamental data analysis techniques, including exploring the dataset, selecting rows and columns, filtering data, sorting values, and identifying missing values.

## Dataset

The airquality dataset contains daily air quality measurements and weather information.

The main variables include:

* **Ozone** – Ozone concentration
* **Solar.R** – Solar radiation
* **Wind** – Wind speed
* **Temp** – Temperature
* **Month** – Month of observation
* **Day** – Day of observation

## Tools and Technologies

* Python
* Pandas
* NumPy
* Jupyter Notebook
* `pydataset`

## Data Import

The dataset was loaded using the `pydataset` library.

```python
import pandas as pd
import numpy as np
from pydata set import data

df = data('airquality')


## Analysis Performed

During this project, I performed several data exploration and manipulation tasks, including:

* Imported and explored the Air Quality dataset
* Displayed the first and last rows of the dataset
* Examined selected rows and columns
* Selected specific columns such as `Ozone`, `Solar.R`, and `Temp`
* Created a new DataFrame from selected columns
* Used `head()` to display the first records
* Selected the first 10 rows of the dataset
* Identified missing (`NaN`) values
* Filtered data based on different conditions
* Sorted and manipulated data using Pandas

## Example: Selecting Columns

python
df_sel = df[['Ozone', 'Solar.R', 'Temp']]
df_sel.head()


This creates a new Data Frame containing only the **Ozone, Solar Radiation, and Temperature** columns.

## Example: First 10 Rows

python
df_sel.head(10)


The head(10) method displays the first 10 rows of the selected dataset.

## Skills Demonstrated

This project demonstrates practical knowledge of:

* Python fundamentals
* Pandas DataFrames
* Data exploration
* Row and column selection
* Data filtering
* Data sorting
* Handling missing values
* Basic exploratory data analysis (EDA)

## Conclusion

This Air Quality Data Analysis project demonstrates the use of **Python and Pandas to explore, select, filter, and manipulate real-world environmental data**. It helped strengthen foundational data analysis skills that can be applied to larger datasets and more advanced analytics projects.



