# Data Transfer Data Engineer Evaluation

## Steps

1. Clone This Repo
2. Load the staging table from mydb.sqlite into pandas dataframe
3. Count the unique members with relationship code of 0 in each source group
4. Calculate the age of each person and mark the rows where a dependant (relationship code not == 0) is over 17 years old
5. Read the changes.txt file into a pandas dataframe
6. Identify all identical records in the changes.csv that are also in the staging data and produce a dataframe of only the change rows
7. Export the dataframe with only the changed rows as json and parquet files
8. Find the failure_emails for each group in the changes.csv file by looking them up in the database


## Bonuses
1. Organize your code for testability write meaningful unit tests of your code
2. Using the changed rows determine if any are a close match to names the original staging table
3. Describe how we can make this evaluation better

### Notes
Feel free to use us online resources such as stack overflow, google, and pandas documentation as needed.

In additionally we recognise that this can be quite extensive.  it is not failure to not finish, however a short paragraph about
your approach to problems you couldn't finish is also helpful

## Submission
Please Return Your Solution set with its own readme file with any notes on how
to setup and run your code in a zip file and upload to MFT/SFTP server with information provided.
File should be named `my_name.zip` and put in the inbound folder.  You won't have read or list permissions so you won't see file appear after it is uploaded. 





