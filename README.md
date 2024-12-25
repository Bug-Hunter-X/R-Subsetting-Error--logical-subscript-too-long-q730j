# R Subsetting Error: logical subscript too long

This repository demonstrates a common but easily overlooked error in R when subsetting data frames using logical vectors.  The error occurs when the length of the logical vector used for subsetting exceeds the number of rows in the data frame.

The `bug.R` file contains the erroneous code, and the `bugSolution.R` provides a corrected version.  The error is explained within the comments of both files.

## How to Reproduce
1. Clone this repository.
2. Open `bug.R` in your R environment.
3. Run the code. Observe the error message.
4. Open `bugSolution.R`. Run the code to see the correct way to handle subsetting.