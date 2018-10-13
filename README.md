# RetailDW
Datawarehouse for Retail Business - BI built on top
```
Step 01: Profiled the Source data across the Databases <br>

Step 02: Created a Dimensional Model from the E-R model <br>

Step 03: Built ETL Mapping workflow in talend <br>

Step 04: Integrated the input data across various sources into the destination Retail_DW <br>
```
<br>

```
* DATA INTEGRATION *
```
<h2> Illustrations <h2> <br>

-- A workflow of the Complex ETL mappings <br>

![alt text]( https://files.slack.com/files-pri/T8L8NFY75-FDDLTQTV5/download/completeworkflow.jpg "CompleteWorkFLow")

-- Parallelizing loading of Basic Dimensions <br>

![alt text]( https://files.slack.com/files-pri/T8L8NFY75-FDC1AQJMP/download/basicdim1.jpg "Basic Dim")

-- A sample tmap for mapping the source to the destination <br>

![alt text](https://files.slack.com/files-pri/T8L8NFY75-FDDLU1RFH/download/tmap.jpg "Sample Tmap")

-- Complex integration flow across multiple source DBs <br>

![alt text](https://files.slack.com/files-pri/T8L8NFY75-FDC1ASPB3/download/complexmapping.jpg "Complex map")

-- FactTable used to store both the Fact and Rejects <br>

![alt text](https://files.slack.com/files-pri/T8L8NFY75-FDCGEQMK5/download/factstoresales.jpg "Fact Reject")

-- Job Stats used to store various details such as JobID, SORID etc

![alt text](https://files.slack.com/files-pri/T8L8NFY75-FDCK5QFMG/download/job_stats.jpg "JobStats")
