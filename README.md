According to the official Pandas documentation, dataframes are two-dimensional, size-mutable, potentially heterogeneous tabular data structure with labelled axes (rows and columns). Arithmetic operations align on both row and column labels. It Can be thought of as a dict-like container for Series object.

Series primarily contains just one homogenous column with corresponding indices. So, series can be thought of as the data structure for a single column of the pandas dataframe. And in actuality as well, the data is stored in a dataframe as a collection of series. If you use the command type() on any of the columns in the dataframe, you will see that the output is pd.series.

An analogy to understand this is arrays and matrices, or 1D array and 2D arrays. 1D arrays are like the building blocks of 2D arrays, and 2D arrays cannot be made without the existence of 1D arrays
Wrong data" does not have to be "empty cells" or "wrong format", it can just be wrong, like if someone registered "199" instead of "1.9 
