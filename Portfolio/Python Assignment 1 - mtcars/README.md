# 🚗 mtcars Data Analysis Using Python

## Project Overview

This project demonstrates basic **data analysis and manipulation using Python and Pandas** with the `mtcars` dataset. The dataset contains information about different car models and their specifications, such as fuel efficiency, horsepower, weight, and number of cylinders.

The purpose of this project is to practice fundamental Python data-analysis techniques, including exploring a dataset, selecting columns, filtering records, sorting data, and analyzing vehicle characteristics.

## Dataset

The **mtcars** dataset contains information on **32 car models** with several automobile-related variables.

Some important variables include:

* **mpg** – Miles per gallon
* **cyl** – Number of cylinders
* **disp** – Engine displacement
* **hp** – Horsepower
* **drat** – Rear axle ratio
* **wt** – Weight
* **qsec** – Quarter-mile time
* **am** – Transmission type
* **gear** – Number of forward gears
* **carb** – Number of carburetors

## Tools and Technologies

* Python
* Pandas
* Jupyter Notebook
* `pydataset`

## Analysis Performed

The project includes several data-analysis tasks:

* Loaded the `mtcars` dataset into Python
* Displayed the first and last rows of the dataset
* Examined the dataset's structure and columns
* Selected specific rows and columns
* Filtered cars based on different conditions
* Sorted data by variables such as MPG and horsepower
* Worked with columns such as `hp`, `cyl`, and `mpg`
* Performed basic exploratory data analysis

## Skills Demonstrated

This project demonstrates knowledge of:

* Python fundamentals
* Pandas DataFrames
* Data selection and filtering
* Sorting data
* Working with rows and columns
* Conditional filtering
* Exploratory Data Analysis (EDA)

## Example

```python
from pydataset import data
import pandas as pd

# Load the mtcars dataset
df = data("mtcars")

# Display the first five rows
df.head()
```

## Conclusion

The **mtcars Data Analysis Project** provides hands-on practice with Python and Pandas for exploring and manipulating structured data. It demonstrates foundational data-analysis skills that can be applied to larger real-world datasets.
