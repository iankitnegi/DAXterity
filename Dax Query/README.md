### Query all rows and columns from a table
EVALUATE    
CALCULATETABLE ( FactSales )    

### Query only 100 rows from a table    
EVALUATE    
TOPN ( 100, FactSales ) 

### Sort the results by SalesKey in Ascending order 
EVALUATE    
CALCULATETABLE ( FactSales )    
ORDER BY FactSales[SalesKey] ASC    

### Query only a few columns from a table   
EVALUATE    
SELECTCOLUMNS (     
DimProduct,  
DimProduct[BrandName],  
DimProduct[ProductName])   

### Query unique rows from a table
EVALUATE    
DISTINCT ( DimProduct ) 

### Query unique rows from a column of a table
EVALUATE    
DISTINCT ( DimProduct[BrandName] )  

### Query a table and filter row with a condition
EVALUATE    
FILTER (    
DimProduct,     
DimProduct[BrandName]   = "Contoso" 
)   

### Query a table and filter row with a wildcard
EVALUATE    
FILTER (    
DimProduct,  
CONTAINSSTRING( DimProduct[BrandName], "Con?"))   
