# POS-simulator

# Description:
POS terminals located at most of the shopping malls are where you end up paying after having shopped. We have simulatec all the functions which the POS handles.

# Code: 
We have used python as programming language to develop this project.
We have used list comprehension, lambda function, inheritance, tuples, exception handling in this project. Since this is just a prototype we have used sqlite3 as database for backend.

# Working
->Our code can create a new item to be inserted into list of items existing in database.
->It can view the items present in the database.
->It can add items to cart and display the same with subtotal and individual item cost.
->It can also delete an item from  the database.
->At last it can Calculate the total amount of the cart and apply discount at the end.

# item description
item has id, name, price, quantity, date of manufacturing, expiry date

# Exception handling
-> If quantity is <=0 or more than inventory quantity
->If item name or id not in the database
