# Maintenance & Repair Data Analyzation
This project was to create a relational database to combine all of the provided data sets into a relational database. I also need to clean up the data and in terms of missing information or null fields, and also inconsistent formatting. Key to Remeber is that across the data the state and county are the key idnetifiers.

Data
-----
County Tax Rate
--------------------
![msedge_BXcvyc0kEI](https://github.com/JohnBossco/maintenance-and-repair-data-analyzation/assets/108234177/21633840-26cd-4a8b-a30a-88d3870f1604)

Exports By State 2012
-------------------------
![msedge_n8hHtoZ4go](https://github.com/JohnBossco/maintenance-and-repair-data-analyzation/assets/108234177/001056ec-1f2d-4953-a015-72d62ea39684)

Median County Income
------------------------
![msedge_YWkvhXyGW2](https://github.com/JohnBossco/maintenance-and-repair-data-analyzation/assets/108234177/2be9100b-e820-48e6-8376-94fbaf60a38b)

State Tax Rate
-------------------------
![msedge_6fiUZ7k8oM](https://github.com/JohnBossco/maintenance-and-repair-data-analyzation/assets/108234177/cc92ab25-3609-4b65-b7c9-3de31345406f)

Unemployment By County
------------------------------
![msedge_sT5hdrPBq2](https://github.com/JohnBossco/maintenance-and-repair-data-analyzation/assets/108234177/0b4a73da-4f34-4b08-b25d-e56a7989f20a)

Usa County List
------------------------------
![msedge_wy9KKuXpA2](https://github.com/JohnBossco/maintenance-and-repair-data-analyzation/assets/108234177/2e7acaf3-527a-454f-876b-5d189680e19b)

Workforce Wages
-----------------------------
![msedge_4iYD4bKlN3](https://github.com/JohnBossco/maintenance-and-repair-data-analyzation/assets/108234177/0635e2eb-8dee-4387-b0c3-7f1fc815fa13)


Relational Database Visualization
----------------------------------
![msedge_GvDpHxt3w0](https://github.com/JohnBossco/maintenance-and-repair-data-analyzation/assets/108234177/04d9e9bc-0ed4-47e0-b2c7-553ae2f6edb9)

SQL Queries
---------------

2 a) Find all counties that have a state tax rate lower than 4% and an unemployment rate higher than 6%. Sort them by their Annual Total Wages (for all industries) from highest to lowest.
-----------------------------------------------------------------------------------------------------------------------------------------
![msedge_ObY8plUdMe](https://github.com/JohnBossco/maintenance-and-repair-data-analyzation/assets/108234177/327bb271-cddb-43b8-bfe8-31ca662dd967)


2 b) Find the 10 counties with the highest Annual Total Wages in the Service Providing industry that also have a Coefficient of Variation for Ton-Miles greater than 20 (for the year 2012) and a labor force over 7,500.
-----------------------------------------------------------------------------------------------------------------------------------------
![msedge_7hIsp2whj3](https://github.com/JohnBossco/maintenance-and-repair-data-analyzation/assets/108234177/9086cc4d-abce-4205-a337-8d0a538ff4f2)


2 c) Find all counties with an Annual Average Pay under $40,000 and a local tax rate under 3%. Sort them from highest population to lowest.
-----------------------------------------------------------------------------------------------------------------------------------------
![msedge_bo082BnYZU](https://github.com/JohnBossco/maintenance-and-repair-data-analyzation/assets/108234177/111f3770-4bcd-4e1c-9251-69a2e8110bb6)


2 d) Find the 10 counties with the highest population whose 2012 exports value is over 25 trillion and also have a higher Annual Average Establishment Count in Construction than in Manufacturing.
-----------------------------------------------------------------------------------------------------------------------------------------
![msedge_HVzXZOPL5K](https://github.com/JohnBossco/maintenance-and-repair-data-analyzation/assets/108234177/4c890b91-444f-4e64-a25e-773ec1773e57)


Location Store:
-------------------
For every county in the United States and export a list of all counties sorted from highest score to lowest score.
Generate an algorithm that gives a numerical score (ranging from 0 to 100) based on data and key factors that are specified by the customer.
---------------------------------------------------------------------------------------------------------------------------
Customer Specifications: 
Location with relatively low average wages in the service-providing industry; Location with low tax rates; Location with high median income; Location with high unemployment
----------------------------------------------------------------------------

![Code_5bk5wxJ3hv](https://github.com/JohnBossco/maintenance-and-repair-data-analyzation/assets/108234177/831132e1-50db-4c13-be63-8b855c71eeca)

![Code_DA1iUQ2y8U](https://github.com/JohnBossco/maintenance-and-repair-data-analyzation/assets/108234177/d72bdb65-b208-4de9-8a0a-6c0b36744762)



