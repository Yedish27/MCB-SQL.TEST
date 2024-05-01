MCB Assessment:

Execute the file “DB_Prequisite.sql” which will enable you to create the table “XXBCM_ORDER_MGT” and inserts all the data.

Execute the file “DB_Table” which will create the tables below : • XXBCM_ORDER_MGT_CLR : Copy of table “XXBCM_ORDER_MGT” with all cleaned data(eg : remove o from amount to replace with 0) 

• XXBCM_SUPPLIER : Table contain all data about supplier 
• XXBCM_TRANSACTION : Table contain all data about transactions

Compile the package PCG_XXBCM_ORDER from the file DATA_MIGRATION.sql – This will enable you to create the procedures PROC_XXBCM_ORDER_CLEAR, PROC_XXBCM_SUPPLIER and PROC_XXBCM_TRANSACTION.

Execute the file “DATA_INSERT.sql” which will use the package and procedures create in step 3 to insert data in the tables created in step2

Execute the file “DATA_FILTER_VIEW” which will create the views DB_SUMMARY, DB_SECOND_HIGHEST and DB_SUPPLIER_LIST.

TASK 4: execute the file “QUESTION_4.sql” – This will display the summary of Orders with their corresponding list of distinct invoices and their total amount.

TASK 5: execute the file “QUESTION_5.sql” – This file will return details for the SECOND (2nd) highest Order Total Amount from the list.

TASK 6: execute the file “QUESTION_6.sql” – This file will display the List all suppliers with their respective number of orders and total amount ordered from them between the period of 01 January 2022 and 31 August 2022
