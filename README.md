# **Formula 1 - PySpark & Databricks**

## Project files info
Notebooks contain display commands that make notebook a bit unreadable, unfortunately due to end of free trial of Azure I couldn't optimize and re-run them again.


## Project objective
Process received raw data with help of PySpark & Databricks through Azure's Data Factory and Delta Lake in order to present visualizations of most dominant team and driver <br /><br />


## Data source
Information about Formula 1 races since 1950 is taken from Ergast API website under term of educational purpose <br />
Link : http://ergast.com/mrd/ <br /><br />



## Project requirements
+ Ingest all 8 files into the Delta Lake
+ Ingested data must be stored in columnar (parquet format)
+ Must be able to analyze the ingested data via SQL
+ Setup and prepare Azure Data Lake Storage Gen2
+ Join the key information required for reporting and analysis
+ Present visualizations of most dominant team and driver<br /><br />


## Process will look following
<br />
<img src="https://i.gyazo.com/6bf04db4b8cca250b098b5bafe9302f5.png" width="800" height="400">
<br/>


## Results
<br>
<img src="https://i.gyazo.com/c4f90e1bbc8092321f854ba7b73eb9ec.png" width="800" height="400">
<br />
<br>
<img src="https://i.gyazo.com/b258f45677af4d20aa3c7ce5e11182a4.png" width="800" height="400">
<br />






## Technologies & tools
+ Python / PySpark
+ SQL
+ Databricks
+ Azure Data Factory & Delta Lake
