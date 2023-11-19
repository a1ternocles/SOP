# SOP

On it, exercise was about to complete 6 taskes in order to create a professional Data Base using tools like 'Python',
'SQL' & 'Google APIs'. And completing the data base product using tools as 'Looker Data Studio' & 'Tableau' to give full body
for the analytics of a BPO.  

  First, a random data base on google sheets was created using https://www.mockaroo.com/ taking in mind BPOs KPIs as:
* date           
* country
* interactions   
* team_lead
* channel        
* status
* csat           
* coaching
* service_level  
* work_hours
* cpc            
* abs_hours
* id
* full_name
* email

Google sheet data : https://docs.google.com/spreadsheets/d/1ISR4awJLze6OZdZH9YJ6ilTBNXsM-qE6vLz2sQnY6_o/edit#gid=1243498948

It is important to highlight main KPIs from BPO suggested, these are:
* As fictitious company, name chosen was: #CAT CHOOSE
* Coaching completion for Agents
* Service level %
* Channels : Voice, Chat & Email
* Targets: 

          * Service Level 85%
          * CSAT 85%
          * Coaching 100%
  
  An Squema for a DATA WAREHOUSE was attached to this file.

# Python Imports

  In order to show (step by step) how to create a script on python
  that help us to automatize the collection, cleaning and export of the data needed.

  It was used different libraries in order to have the script completed. List below:
* import gspread
          
          from gspread_dataframe import set_with_dataframe
* import pandas as pd
* import mysql.connector as sql
* import sqlalchemy as sa

          from sqlalchemy import create_engine

It is necessary to install these libraries by doing following:

Into py terminal, type:
* pip install gspread
* pip install gspread_dataframe
* pip install pandas
* pip install mysql-connector-python
* pip install sqlalchemy

  Google API's was enabled in order to get access and permissions to use Google SpreadSheets and its functions (json keys used)
  SQL WorkBench was used for the purpose of the exercise

  # Dashboards

  OPS Dashboard Suite: https://lookerstudio.google.com/reporting/4a5eaaa1-d6de-40b4-bbeb-45a915e161b8

  Executive Dashboard Suite: https://public.tableau.com/views/EXECUTIVESuite1/PerformanceperQ?:language=es-ES&publish=yes&:display_count=n&:origin=viz_share_link

# Documentation
Some written sources were used in order to complete taskes:
* Markdown Sintaxis: https://github.com/ricval/Documentacion/blob/master/Markdown/daringfireball/syntax.md
* Color code usage: https://paletadecolores.online/pastel/
* Pandas Library and methods : https://aprendeconalf.es/docencia/python/manual/pandas/
* Data connection using pandas : https://medium.com/geekculture/2-easy-ways-to-read-google-sheets-data-using-python-9e7ef366c775
