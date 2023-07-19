#                               Data-cleaning-Exercise-in-Excel
**This exercise is carried out to solidify my data cleaning skill**
The dataset used in this lab comes from the following source: https://data.montgomerycountymd.gov/Government/Fleet-Equipment-Inventory/93vc-wpdr under a Public Domain license.

The raw dataset is made up of 3 categorical variables (columns) and 1 numerical variable(column).
These are the columns of the dataset and their data type
*Department column - TEXT
*Department column - TEXT
*Equipment class - TEXT
*Equipment Count- Numeric

#                                   Data cleaning process
* **Column widths:** I Sorted out the widths of all columns so that the data is clearly visible in all cells.

* **Empty rows:** I Used the Filter feature to look for blanks and remove all empty rows from the data.

* **Duplicate records:** I Used either the Conditional Formatting or Remove Duplicates feature to look for and remove any duplicated records from the data.

* **Spelling:** The original source file data has not been checked for errors in the spelling. I Checked for spelling mistakes in the data and fix them.

* **Whitespace:** I Used the Find and Replace feature to remove all double-spaces from the data.

* **Department names:** When the data was converted from its data source, the department names (see correct list below) didn’t import correctly and they are now splited over two columns in the data. I Used Flash Fill to reduce the department names to just one column, and then remove any unnecessary columns
                              | **Department** | **Department** |
                              |----------------|----------------|
                              |Board of Election|Economic Development|
                              |Circuit Court|Environmental Protection|
                              |Community Engagement Cluster|Finance|
                              |Community Use of Public Facilities|Fire and Rescue|
                              |Consumer Protection|General Services|
                              |Correction and Rehabilitation|Health and Human Services|
                              |County Executives Office|    |

