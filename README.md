# CMIP6-Input-Scripts

This repository is an archive of scripts that may have been used to create model input files from CMIP6 forcings. The scripts are preserved as-is. They are being preserved for provenance purposes. There is no intention to modify or update them. 

If updated or replacement scripts are needed for CMIP6 or CMIP7 forcings, please use either the https://github.com/ACCESS-NRI/CMIP7-Input repository or the [MOSRS ancil/contrib](https://code.metoffice.gov.uk/doc/ancil/ants/latest/contributing.html#contribute-code) repository as appropriate. For more documentation on CMIP forcing processing, see the [ACCESS-NRI/CMIP7-Input Wiki](https://github.com/ACCESS-NRI/CMIP7-Input/wiki).

## Directory structure

* `scripts`

  Scripts used to process CMIP6 forcings into model inputs.

* `scripts/mrd599/src/python`

  Python scripts selected from `gadi:/home/599/mrd599/src/python` and not contained in other repositories. These are scripts containing functions imported by some of the Python scripts in `scripts/txz599/ACCESS-ESM_tools`.

* `scripts/txz599/ACCESS-ESM_tools`

  Scripts selected from `gadi:/g/data/p66/txz599/ACCESS-ESM_tools` and not contained in other repositories. Some of these scripts were used in the processing of CMIP6 forcings into ESM1.5 inputs.
