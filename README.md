# INTERNSHIP TEST

This repository contains solutions for the technical test of the Data Engineering Internship at 99 Group.

## Description

In this project, I developed an **ELT (Extract, Load, Transform)** pipeline system by executing the correct sequence of SQL files based on their dependencies. The system is designed to clean, transform, and consolidate data from multiple source tables into the final table in the data warehouse.

## Steps:

**SQL File Preparation:** All SQL files are sorted based on their respective dependencies. The SQL files in the source and tmp folders are executed first, before those in the final folder.

**SQL Execution:** The simulation uses the time.sleep(2) function to mimic the execution time of SQL files.

**Dependency Handling:** The program ensures that each SQL file is executed in accordance with its dependencies.

## How to run the code:

**Google Colab Link**:  https://colab.research.google.com/drive/1_vvuj4j_mG-1l14POxPMh6OW96Zm_GGY?usp=sharing

## Depedency:
There are no external dependencies aside from **Python**.

## SQL File:
The SQL files used are located in the **sql** folder.
