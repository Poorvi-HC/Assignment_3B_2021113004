# Assignment 3B

## Given Stock data for 5 days, analyze the input given by the files using tools in python, like sqlite. 
### a) Provide the data in a tabular format and assign confidences given as per the constraints mentioned in the control table.
### b) To analyze the stocks of the companies over multiple days and observe the growth or depreciation of the stock value. Outputting out the metrics such as the highest performing company, gain%, worst performing company, loss% to name a few.
<br>

## Setup
### 1. Create a Folder (Name of folder is your \<Roll Number>)
### 2. Place 5 Comma Separate files inside the folder. Name, these files as below
#### \<Your Roll Number>-<Date 20-05-2022>.csv <br>
#### \<Your Roll Number>-<Date 21-05-2022>.csv <br>
#### \<Your Roll Number>-<Date 22-05-2022>.csv <br>
#### \<Your Roll Number>-<Date 23-05-2022>.csv <br>
#### \<Your Roll Number>-<Date 24-05-2022>.csv <br>
### 3. Create another Folder. Name it as Control
### 4. Inside the Control folder, create file and name it as control-table.csv. Schema and details are mentioned in tab: Control Table of excel sheet
### 5. Create a database Record.
### 6. Create two tables in database - Record. Name them Ticker & Metrics.
### 7. The schema of the tables and associated instructions are mentioned in tab: Table – Metrics and Table - Ticker of excel sheet

## Constraints considered by me:
### New industries and companies are added to the list as and when it is added
### As confidence is not specified for one input count doesn't consider it

## How to run the database in sqlite3
```
    > sqlite3
    > .open record.db
    > SELECT * FROM Ticker
    > SELECT * FROM Metrics
```
