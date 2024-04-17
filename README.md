# HydroFlows-data

This repository hosts large test data for [HydroFlows](https://github.com/Deltares-research/hydroflows). This data is stored as artifact data to the [data release](https://github.com/Deltares-research/hydroflows-data/releases/tag/data) on GitHub. The large test data is downloaded automatically by HydroFlows tests using fixtures when running the tests and stored in the `<hydroflows-repos>/tests/_large_data/data` directory.

## Data licenses

Each dataset has its own license. The license is either stored in the data archive with the name `LICENSE.txt` or is mentioned in the `data_catalog.yml` which has an entry for each dataset.

## Updating the data

Follow the instructions in the `<hydroflows-repos>/tests/_large_data/data/README.md` file to update the data.