# Palestine-Purchase-Certificate
Application has 2 main screens, the first screen has a single upload button accepting CSV files,and the second screen has a single click button , when we click on it, a new file contains the purchase certificate can be download.


The system should handle the uploaded file, process the rows inside row-by-row, save the correct rows in DB.
The downloaded file name should have the merchant admin page name, every purchase certificate can only have 4 rows, we need to verify the file structure also it should contains all the  necessary data of the orders, every row in the Certificate is about parcel, and after downloading the row we shouldn’t process it again or the Purchase Certificate number. 
