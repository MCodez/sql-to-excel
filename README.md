# sql-to-excel
## This repository will provide you Python3 code to convert SQL Database to Excel Workbook.

This Python3 code can convert SQL Database (.sqlite) {with corresponding tables} to Microsoft Workbook (.xlsx) {with many sheets}. 

## Packages Required :
1. OPENPYXL {can be installed by pip : pip install openpyxl}
2. SQLITE3  {can be installed by pip : pip install sqlite3}
3. PYTHON 3.6 {python.org}

## Command :
```console
py@bar : python sqltoexcel.py <workbookname> <sqldatabasename>
```

## Working :
1. Each sheet will be created for each table in database.
2. First row of sheet will be same as the columns names of SQL Table.
3. None rows in SQL TAble will be removed. 
