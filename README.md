# dbt study
This repository was created in order to help me get more familiar with dbt's concepts and utilities.

## Setup
This repository uses poetry as its dependency manager.

## dtb demo
The dbt project contained in this repo was largely based in [dbt's quickstart tutorial for dbt core](https://docs.getdbt.com/docs/quickstarts/dbt-core/manual-install).

This simple project can illustrate some of dbt's coolest capabilities: easily creating views from .sql files, choosing whether or not to materialize them into tables, referencing other models inside the definition of models, creating data quality validation tests, and documentation.

## Connection to data warehouse
BigQuery was utilizided as a proxy of a data warehouse for this project because of its free tier and convinece.

In order to setup a project in BigQuery, you can follow [these steps](https://docs.getdbt.com/docs/quickstarts/dbt-cloud/bigquery), which also teaches you how to create credentials that will allow you to connect dbt to BigQuery.
