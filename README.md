# Basic_IBMDB2_project

Included are queries to reconstruct the database and a report.
This database is created on IBM DB2.

It is recommended that you use the lastest version of db2 to avoid errors.

The order in which the triggers are created is VERY
important as the order in which it excutes depends on the order
it is created.The order are as follows:

1)Trigger 1(get_detailsPrice)
2)Trigger 2(get_detailsPriceUpd)
3)Trigger 3(inv_totalPriceUPD)
4)Sub queries(inv_totalPriceDel)
5)Aggregate function(inv_totalPriceIns)

A 'queries' text document is included for reconstruction of the database.

Thank you for your time!
