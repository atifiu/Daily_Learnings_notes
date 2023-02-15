1. ## 15-Feb-2023

    - ##### Iterable in python: 
        String, list, dictionary. To check if object is iterable use it at the end of for loop or use iter() method on it.  
        Reference: https://twitter.com/s_gruppetta_ct/status/1625544155786285057

    - ##### Use of Parquet file: 
        Use parquet file in place of csv, as parquet file requires less memory and hence better performance in reading and save storage. Can be easily read by pandas.  
        Reference: https://twitter.com/paulabartabajo_/status/1625495124011798531

    - ##### PivotTableJS 
        Lets you interactively analyse your data in Jupyter Notebooks without any code.  
        Reference: https://twitter.com/akshay_pachaar/status/1625472450288041985

    - ##### Added plotly dumbell plot
        Plotly Dumbell plot has been added to https://github.com/atifiu/dumbell_plot repo  

    - ##### Dir method
        Dir method can be used to list all available method on any python object using dir(objact_name)  
        Reference: https://twitter.com/CodingComputing/status/1625767054157713408

    - ##### PSQL to execute script on windows only
        "C:\Program Files\PostgreSQL\14\bin\psql.exe" -h hostname -d postgres -U postgres -p 5432 -a -q -f E:\postresql_db\demo-medium-en\demo-medium-en-20170815.sql  
        Reference: https://stackoverflow.com/questions/9736085/run-a-postgresql-sql-file-using-command-line-arguments  

    - ##### ROLLUP in SQL
        Rollup function is used in group by to total/sub total based on group. Multiple rollup are supported.   
        Query:  
            `select count(1), status, aircraft_code  from flights  
    group by rollup( aircraft_code, status)  
    order by  aircraft_code, status;`  
    ![table](/table.jpg)  
    Reference: https://www.youtube.com/watch?v=5xq7BSkKAF8  
        

---
