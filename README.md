# MMRates from DHS survey data

This tutorial shows how to calculate age-disaggregated maternal mortality rates (MMRates) from DHS survey data in R, using the sisterhood method.

The `mmrate_data.csv` file is a subset of the full DHS VI model data. If starting with the full dataset (available [here](https://dhsprogram.com/data/Download-Model-Datasets.cfm)), remove the `eval=FALSE` chunk option from the first five chunks of the notebook and delete the chunk that reads in the CSV subset (lines 89-91).
