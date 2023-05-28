# No-SQL challenge

## PROJECT DESCRIPTION

This code will extract data from the eestablishments.json files in the Resources folder and evaluate some of the ratings data in order to help UK food journalists and food critics decide where to focus future articles
## HOW TO RUN THE PROJECT

### Python Script:

Download the Resources folder and NoSQL_setup_starter.ipynb & NoSQL_analysis_starter.ipynb files, and open VSCODE or Jupyter Notebook to run the script. 

To run the script you will need to have installed pymongo,pandas & pprint libraries.

### Note:

Before running the python script, you will need to run 'mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json' in the terminal to load the mongodb with establishments database. Move into Resource folder in terminal and run the db import command

