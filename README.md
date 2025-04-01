We want to rename a column in a pandas DataFrame, Rename columns using the rename metho, Notice that the rename method can accept a dictionary as a parameter. We can use the dictionary to change multiple column names at once
Using rename with a dictionary as an argument to the columns parameter is my preferred way to rename columns because it works with any number of columns. If we want to rename all columns at
once, this helpful snippet of code creates a dictionary with the old column names as keys and empty strings as values.
