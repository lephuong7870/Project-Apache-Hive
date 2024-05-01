# Project-Apache-Hive


+----------------+      +----------------+      +----------------+      +----------------+      
|                |      |                |      |                |      |                |     
|  Web scraping  | ---> |  Staging Area  | ---> |  Data Cleansing| ---> |  Data Lake     | 
|  Multiple      |      |                |      |                |      |                |    
|  Sources       |      | (Raw Import)   |      |   (Transforms) |      |   (Aggregated  |   
|                |      |                |      |                |      |      Data)     |      
+----------------+      +----------------+      +----------------+      +----------------+     
                         |                |      |                 |
                         |  Data Quality  | ---> |  Data Enrichment|
                         |   (Checks)     |      |   (Add Context) |
                         +----------------+      +-----------------+
