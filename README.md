# DSA-EXCEL-CLASS--VLOOK-UP-
This is where I input all I learnt in the VLOOKUP Class.
# Project Topic:  Optimization of the VLOOKUP function

## Table of Contents
- [Project Overview](#Project-Overview)
- [Data Sources](#Data-Sources)
- [Tool Used](#Tool-Used)
- [Data Cleaning and Preparation](#Data-Cleaning-and-Preparation)
- [Explorative Data Analysis](#Explorative-Data-Analysis)
- [Data Analysis](#Data-Analysis)
- [Result/Findings](#Result/Findings)
- [Recommendations](#Recommendations)
- [Limitations](#Limitations)
## Project Overview.
The aim of this project is to use VLOOK UP function to fetch data from one table to another. With vlookup one can avoid mechanical process of sorting out data to fit into another table.

### Data Sources
The data used for this project was shared in the class.
### Tool Used
- Ms Excel for data collection [Download Here](https://www.microsoft.com)
Excel spreadsheet was used for this class.
### Data Analysis
Here, we were able to apply the function of vlookup and learnt the types of cell referencing which made the vlookup function like a magic wand.  They are:
- Relative	Q5
- Absolute	$Q$5
- Column constant	$Q5
- Row constant	Q$5


This is because by the time we used the right referencing for our formula, we could drag our cursor down and to the right and it will fetch the right figures from our table of reference.
the vlookup function has 4 arguments, which are:
- Lookup value: is what exist between where you are sitting and what you want to return.
- Table array: this is where you want to return something from.
- Column Index number: this is the position of the column that you want to return something from; it could be the 1st, 2nd or 3rd column
- Range_lookup: this is finding the match. it could be exact match(0) or approximate lookup match(1). The former looks for the exact, the latter looks for something close to it when the exact is not found.

### Result/Findings
Here is the formula we used for the class

```` Excel
=VLOOKUP($E9,'Simple Salary Structure'!$B$7:$I$16,F$7,0)
