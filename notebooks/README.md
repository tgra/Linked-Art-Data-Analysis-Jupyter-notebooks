
# Jupyter notebooks

## Important - use of stored shared variables 
The notebooks make use of shared variables stored in the variables.ipynb file.

Before running the datavis and summary notebooks, you will need to execute the variables.ipynb notebook to store the variables defined, so that they are available for the other notebooks.


## Open notebooks 

### Jupyter notebook
From root dir, ie directory above notebooks, ../notebooks, in terminal use command: 

`jupyter notebook`

This will open browser with directory.

- Run the `variables.ipynb` notebook first to store variables that are used across the notebooks.


## Trust notebooks

To trust notebooks use the following commands before opening the notebooks 
`jupyter trust variables.ipynb`
`jupyter trust datavis/*`
`jupyter trust create_summary_files/*`

### VisualStudio Code
Add the Jupyter notebook extension to VisualStudio Code to run the notebookes in the IDE.