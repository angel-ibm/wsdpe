# Exercise 2

## Presto SQL  

Bitte führen Sie die folgenden Sektionen des watsonx.data Lab.  

!!! abstract "Exercise 2.1"
    - [Analytic Workloads](https://db2-dte-poc.github.io/wxddemo/wxd-analytics/)
    - [Advanced Functions](https://db2-dte-poc.github.io/wxddemo/wxd-advanced/)
    - [Time Travel](https://db2-dte-poc.github.io/wxddemo/wxd-timetravel/)
    - [Federation](https://db2-dte-poc.github.io/wxddemo/wxd-federation/)
    - [Apache Superset](https://db2-dte-poc.github.io/wxddemo/wxd-superset/)

Im Kapitel **9. Federated Queries** und **11. Time Travel and Rollback **aus dem **[Zusätzliches Material](https://angel-ibm.github.io/wsdpe/extra/)** haben Sie sehr ausführliche Informationen und ergänzende Übungen zu diesem Thema.

Ganz am Anfang, im Abschnitt **Joins and Aggregations** gibt es ein kleines *"quiz"*. Wenn Sie hier nicht weiter kommen, wäre das ein Versuch:

??? tip "Quiz: window function"

        SELECT 
           custkey, orderdate, totalprice, 
           lag(totalprice, 1) OVER (PARTITION BY custkey ORDER BY orderdate asc) AS priororder
        FROM 
           iceberg_data.workshop.orders 
        ORDER BY 
           custkey, orderdate;



## Working with Object Store Buckets

Bitte führen Sie die folgenden Sektionen des watsonx.data Lab.  

!!! abstract "Exercise 2.2"
    -  [Object Store](https://db2-dte-poc.github.io/wxddemo/wxd-objectstore/)

Im Kapitel **7. Working with MinIO** aus dem **[Zusätzliches Material](https://angel-ibm.github.io/wsdpe/extra/)** haben Sie sehr ausführliche Informationen und ergänzende Übungen zu diesem Thema.

## Installation von watsonx.data

Wenn Sie die Installation von watsonx.data in der letzten Übung durchgeführt haben, können Sie jetzt den näachsten Schritt durchführen, um die Installation zu vervollständigen.

!!! example "Exercise 2.3"
    - [Installation watsonx.data **Step 3**](https://pages.github.ibm.com/alexander/ibmas-watsonxdata/Execute%20the%20Installation%20of%20watsonx.data/)