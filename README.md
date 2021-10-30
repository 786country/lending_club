# lending_club
 Lending Club Data Machine Learning Model

1. Installation 

The anaconda distribution of anaconda will cover most packages, however the following package(s) will be required to be installed: 

`missingno`

This can be installed in anaconda using the following command: 

`conda install -c conda-forge missingno`

2. Project Motivation 

This dataset was chosen because a college recommended it to me because of the data cleansing challenges it presents, coupled with my previous experience in the loan default arena, I decided to take a stab at it. 

3. File Descriptions 

The Files are listed in the below table. (ignoring repository standard files)

| File Name              | Description                                           |
|------------------------|-------------------------------------------------------|
| functions.py           | Helper functions used in the main code located here   |
| LCDataDictionary.csv   | Data Dictionary describing each column in the dataset |
| lending_club_loans.csv | Actual Data used for the project                      |
| lending_club.ipynb     | Notebook used to perform data engineering/science     |

4. Project Challenges 

The technical challenges are listed below: 

a) The large amount of columns at first was overwhleming, however after some basic data quality checks (null percentages, high cardinality and constant columns) the columns reduced from the intial amount of 115 to 40 columns. 

b) The next step was to check for columns that were identical, this also assisted in reducing the final amount of columns to analyse.

c) As there were different types of categorical columns different methods were used to treat them, Ordinal -> Label Encoding and categorical -> one hot encoding 

d) Row wise null treatment, This took some time exploring the different visualisations of the columns and then deciding on the best approach for each 

5. Licensing, Authors and Aknowledgements 

Licensing: MIT can be located in the LICENSE file on the repo 

This work could not have been possible without the help of my friend and college Luqmaan Hassim, he was instrumental in giving advice throughout its development. 