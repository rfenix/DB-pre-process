# DB-pre-process
Google script to delete rows that have no data in some sheet columns or exceed limits on the first column called Birads on the database.


The function deleteRows get the values from the sheet and look for "?" character, when it's found the entire row is deleted.
The function deleteBirads get the values from the class column on the sheet(Bi-rads), look for values that less than 1 and bigger than 5, then delete the entire row.

This is the link of the database:
http://archive.ics.uci.edu/ml/datasets/mammographic+mass

In my sheet, the data started at line 8.
