# Auto Merger in Fabric Spark

This set of notebooks demonstrates how to load multple tables from incremental files using structured streaming on a single Spark cluster. The loading process by default occurs as quickly as possible using a merge statement. This demo uses sample data taken from the Fabric lakehouse tutorial: 

https://learn.microsoft.com/en-us/fabric/data-engineering/tutorial-lakehouse-data-ingestion
https://learn.microsoft.com/en-us/fabric/data-engineering/tutorial-lakehouse-data-preparation

Import the three notebooks in this repository and start with the Instructions notebook

Latest features:
Ability use a metadata file containing tables, primary key and dense rank sort key.
