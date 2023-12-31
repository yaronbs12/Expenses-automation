# Expenses automation
Hello and welcome to my project!

This project is a Python script that automates the process of organizing personal expenses.
It uses pandas, openpyxl, and regex libraries to read expense reports from an Excel file and reorganize
them into a unified format, update dates for transactions with multiple payments, and add new
expenses to the main expenses file.

The output is a pivot table and advanced pivot charts that help to understand the expenses in detail.
Overall, this project saves time and effort by automating a tedious and error-prone task, allowing for better financial management.

Some important points:

-The project is using Excel reports that I downloaded from my israeli credit card company "MAX".

-At the beginning of the code there are some variables that you should change in order to use the code:

**EXPENSES_PATH**- The path to the Excel file, where all the expenses are shown.

**FOLDER_PATH**- The path to the folder with all the monthly expenses files.

**SUBSCRIPTIONS**- If you have any subscriptions(like Spotify or Netflix), write them in as an array.

**SAVING_DEPOSITS_DIC**- If you have Regular expenses for savings that are charged directly from the bank account, write it down 
as a dictionary with the amount. (For example: {"SAVING_NAME":1000})

Some notes:
-The whole Excel file will be in Hebrew for convenience.
-All the shown data are examples with randomly generated values. Only the format of the files remain the same.

Enjoy!
