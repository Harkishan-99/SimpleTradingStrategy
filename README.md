# SimpleTradingStrategy

This repository contains a simple momentum trading strategy which uses data from the `equities` database which is provided as an SQL source file.

## Implementation Guide

- Install the requirements.
- Modify the config file with your SQL server credentials. 
- Start by ingesting the data by running `python ingest_data.py`.
- Run a data integrity and datatype check using `python -m unittest`
- Now the jupyter notebook of the trading strategy can be explored.