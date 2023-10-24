# ev-chicken-egg (data processing)

## Introduction
The file is US_Fleet_County_2021Q4.parquet too big to run on laptop so we are processing data using two methods.

1. Process a smaller chunk to find out all necessary steps
    - We do not have all possible mappings of all data to its general categories so we have manually mapped it to corresponding categories.
    - copy the final dictionary from `manual_cat_dict.ipynb` to your main file.
    - `!!! Important` Please verify `cols_value_cat` values in that dictionary.
2. Run entire file on HCC
    - copy all the cells from *main.ipynb* to *main.py* and submit the job. 