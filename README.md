# ETL
1. By visually inspecting the Data.xlsx sheet, it is found that the row in which the Name/Email ID/Phone number is missing would be considered as 'bad data' since those informations are considered crutial in analysing the data extracted.
2. Hence, Row 5,6,7 are considered to be bad data.
3. Depending on the type of analysis if some piece of information is missing from the Address column can also be considered as "bad data" as in row 6 & 8 address is incomplete.
4. Along with the missing data, it is also found that in row 1 the date is declared in String format. Where as in rest of the rows "Collection_Date" the data type is "Date". This has been altered when processing the data into Gold/Bronze tier.
5. Using nodejs I was successfully segregate customers into Gold/Bronze tier based on the criteria mentioned in the assignment.
