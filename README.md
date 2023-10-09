# Dotmim.Sync.SampleConsole

Cascade applied on SQLite 'Product' table -> referencing ProductCategoryID in ProductCategory table, 
To Avoid Errors, 
- removed the ForeignKey reference to ProductID , from SalesOrderDetail  table 
- removed the ForeignKey ParentProductCategory referencing ProductCategory in same table.
