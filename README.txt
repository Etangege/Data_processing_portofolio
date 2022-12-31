This is a data processing code created with Jupyter Notebook with VScode using Python 3.0.
the purpose of this code is to merge 4 dataset from 2 database and directly upload to a certain google sheet automatically
this program runs sub 1 minute (30 to 40 seconds) processing 10k data from a single dataset 

how to use:
- download SAP file using preffered Setting
- add 'X' to source-reporting, Lead ID, add '-Marketing' to 2nd Email column, and Opportunity ID
- change name to 'PREFFEREDNAME1'
- download agent list (change to PREFERREDNAMES2)
- download agent weekly report (change to PREFERREDNAMES3)

#note
few merging cannot be used with primary key due to differences in databases primary key and/or bad primary key between 2 databases
