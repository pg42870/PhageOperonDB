# PhageOperonDB

The PhageOperonDB repository contains the data and files used to develop the PhageOperonDB, a MySQL database of phages' operons.

## Data Collection
In this folder, you will find the files retrieved from the PhiSITE database of the promoters and terminators of phages.
With this file, we obtain a list of bacteriophage species that have known promoters and terminators ('bacteriophages_list.txt').
The code created is in the JupyterNotebook 'PhiSite information.ipynb'.

Through this species list, we could, manually, find phages' operons and compile the information on the phages.xlsx file.

## Construction of the DB
The creation of the database could be found in the PhageOperonDB JupyterNotebook in this folder.
All the files originated in this notebook are also present, as well as the files used to create the tables in the database.

The  Jupyter Notebook 'Operon_information.ipynb' is used to retrieve the data from the phages.xlsx file in order to insert this data in the database.

