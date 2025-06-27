# GeomeTRe_results
GeomeTRe calculation results for STRPs from RepeatsDB v4. Reproducible Jupyter Notebook scripts are available in this repository.


##------- Prepare data files for analysis -------------##
# Output csv file of GeomeTRe and json files of the RepeatsDB database used to get
# classification and repeat unit number information from RepeatsDB. .json file can be retrieved via API (https://repeatsdb.org/api)
# test files in test_data directory


* repeatsdb4_classification.json - 

* repeatsdb4_units_filtered.tsv - Input file for the GeomeTRe software providing PDB ID and unit/insertions annotations as provided in RepeatsDB version 4. 
Low quality annotations were manually removed.

* repeatsdb4_geometre.csv - GeomeTRe calculation of input_repeatsdb_v4_filtered.tsv



