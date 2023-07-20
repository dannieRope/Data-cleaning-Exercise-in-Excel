#                               Data-cleaning-Exercise-in-Excel
**This exercise is carried out to solidify my data cleaning skill**

The dataset used in this exercise comes from [here](https://data.montgomerycountymd.gov/Government/Fleet-Equipment-Inventory/93vc-wpdr) under a Public Domain license.

The raw dataset is made up of 4 columns and 63 rows including header and blank rows
Below are the columns of the dataset and their data types


*Department - TEXT*

*Equipment class - TEXT*

*Equipment Count- NUMERIC*

![Screenshot (352)](https://github.com/dannieRope/Data-cleaning-Exercise-in-Excel/assets/132214828/25e0164a-05a7-4646-93da-848af18f3e89)

##                                   Data cleaning process
* **Column widths:** I Sorted out the widths of all columns so that the data is clearly visible in all cells.

* **Empty rows:** I Used the Filter feature to look for blanks and remove all empty rows from the data. A total of 5 rows was removed in this process.

![Blanks](https://github.com/dannieRope/Data-cleaning-Exercise-in-Excel/assets/132214828/42aeed5f-20a3-4a9d-9d4c-5be566bb8442)

  

* **Duplicate records:** I Used the Remove Duplicates feature to look for and remove any duplicated records from the data. A total of 8 duplicates values were found and removed.

![remove duplicates](https://github.com/dannieRope/Data-cleaning-Exercise-in-Excel/assets/132214828/30b8e4fa-313b-4107-9838-725095e1ee6d)


* **Spelling:** The original source file data has not been checked for errors in the spelling. I Checked for spelling mistakes in the data and fix them. During this process 5 words spelt wrongly were fixed.

![spell checking](https://github.com/dannieRope/Data-cleaning-Exercise-in-Excel/assets/132214828/0a807d6e-3b8f-4ee4-aee0-108be4e0ea05)


* **Whitespace:** I Used the Find and Replace feature to remove all double-spaces from the data. 3 replacements were made. I also used the TRIM() to remove single spaces

![Find and replace](https://github.com/dannieRope/Data-cleaning-Exercise-in-Excel/assets/132214828/7e3a4746-8568-4bf1-890c-1f2d0ac9ab20)
  

* **Department names:** When the data was converted from its data source, the department names (see correct list below) didn’t import correctly and they are now splited over two columns in the data. I Used Flash Fill to reduce the department names to just one column, and then remove any unnecessary columns

  
   | Department| Department|
   |----------------|----------------|
   |Board of Election|Economic Development|
   |Circuit Court|Environmental Protection|
   |Community Engagement Cluster|Finance|
   |Community Use of Public Facilities|Fire and Rescue|
   |Consumer Protection|General Services|
   |Correction and Rehabilitation|Health and Human Services|
   |County Executives Office|    |


