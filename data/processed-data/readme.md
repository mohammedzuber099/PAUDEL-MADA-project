# processed-data

This folder contains data that has been processed and cleaned by code.

Any files located in here are based on the raw data and can be re-created running the various processing/cleaning code scripts in the `code` folder.

The folder contains four different datasets.

1. `processeddata.rds` : dataset generated by processing and cleaning of the data by `processing-code.qmd` file.
2. `processeddata.xlsx`: `xlsx` version of the above mentioned dataset.
3. `train-data.rds` : training dataset used in the project, created by `analysis-code.qmd` file.
4. `test-data.rds` : testing dataset used in the project, created by `analysis-code.qmd` file.