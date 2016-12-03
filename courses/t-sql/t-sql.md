- NULL means -> UNKNOWN or missing value

- 2 + NULL = NULL
'MyString´+ NULL = NULL

- Equality comparison
    ```
    NULL = NULL returns false 
    NULL IS NULL returs true 
    ```
`function ISNULL(column/variable, returns value)    `

`function COALESC(column/variable, column/variable)`
this returns the first non value in the list


ORDER BY
OFFSET <offset_value> ROW(S)
FETCH FIRST|NEXT <fetch_value> ROW(S) ONLY

Filtering and Using predicates
------------------------------

| Predicates and Operators | Description                                           |
---------------------------|-------------------------------------------------------|
| = <>                     | Compares value for equality / non equality            |
|--------------------------|-------------------------------------------------------|
| IN                       | Whether a specified value mathches any value in a     |
|                          | subquery                                              |
|--------------------------|-------------------------------------------------------|
| BETWEEN                  | Wether a specified value mathches any value in a      |
|                          | subquery                                              |
|--------------------------|-------------------------------------------------------|



- Views are names queries with definitions stored in a database
- Temporary tables are used to hold temporary result sets within a user´s session #
- Table variables introduced because temporary tables can cause recompilations @ (Use only on very small datasets, no more than 100 rows)
- Table-Value Functions are named objects with definitions stored in a database
- Derived Tables are named queries expressions created within an outer SELECT statement 
- Common Table Expression are named table expressions defined in a query

/*
	Challenge 1
*/

--1

SELECT P.ProductID, p.Name,
	  PM.Name  as ProductModelName, PM.Summary
FROM SalesLT.vProductModelCatalogDescription as PM
JOIN SalesLT.Product as P
ON P.ProductModelID = PM.ProductModelID;

--2

DECLARE @TableColor as TABLE( Colors varchar(max))

INSERT INTO @TableColor
SELECT DISTINCT(Color) 
FROM SalesLT.Product

SELECT P.ProductID, P.Name , P.Color
FROM SalesLT.Product as P
JOIN @TableColor as C
on P.Color = C.Colors

--3
SELECT P.Name, C.ParentProductCategoryName , C.ProductCategoryName
FROM SalesLT.Product as P
JOIN dbo.ufnGetAllCategories() as C
on P.ProductCategoryID = C.ProductCategoryID

/*
	Challenge 2
*/



WITH CustomerSales(CompanyContact, SalesAmount)
AS
(SELECT CONCAT(c.CompanyName, CONCAT(' (' + c.FirstName + ' ', c.LastName + ')')), SOH.TotalDue
 FROM SalesLT.SalesOrderHeader AS SOH
 JOIN SalesLT.Customer AS c
 ON SOH.CustomerID = c.CustomerID)
SELECT CompanyContact, SUM(SalesAmount) AS Revenue
FROM CustomerSales
GROUP BY CompanyContact
ORDER BY CompanyContact;


Grouping Sets
--------------

Rollup & Cube

- Rollup provides shorcut for defining grouping sets with combinations that assume input columns from a hierarchy
- Cube provides shorcut for defining grouping sets in which all possible combinations of grouping sets created

Pivot & Unpivot

Inserting data
--------------

**Sequence

``` 
	Create Sequence [schema].[name] as INTO
	STARTS WITH 1 INCREMENT BY 100
	
	SELECT NEXT VALUE FOR [schema].name
	
```




