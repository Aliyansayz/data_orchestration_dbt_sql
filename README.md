# data_orchestration_dbt_sql


## Data Build Tool

* yaml `profiles` (In linux:-  ~/.dbt/profiles.yml ) can be made inside project directory too,
* yaml `dbt_project`  (inside proeject directory deals with models materialization upstream downstream of )
* yaml `_source__source_name` (usually inside staging)
* Use of `ref` , `config` `config(materialized)`
* Use of dbt debug
* use of dbt run with some flags
* Materialization, Data Lineage, Table vs View
* Folder Structure of dbt models for staging, marts

## Schemas
* Schema types
* Avoiding data replication
* Modeling of tables like one to many, one user id can have many posts id but inverse is not possible
* Fact table vs dimension table

  
## SQL

* sql Notebooks
* sql commands in data staging, transformation(intermediate), marts
* CTE Tables, CTEs for count records, max min and mean record, for cummulative of numerical feature spending
  

  
Use of data orchestration in data build tool use of .yaml for connection, source, model materialization and sql
