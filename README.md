# NoahMP Forcing scripts

This repository contains scripts and utilities for working with NoahMP land surface model.

July 2025 Update:
NLDAS recently changed their data format from GRIB to NetCDF (https://disc.gsfc.nasa.gov/datasets?keywords=NLDAS). The new extraction scripts  handle this transition while keeping the NoahMP workflow unchanged.

## Scripts

apcp.py - Processes precipitation data with proper accumulation metadata

init.py - Extracts initial condition variables and converts them to GRIB format

extract_nldas.perl - Extracts: Downward longwave radiation flux (W/m²), Downward shortwave radiation flux (W/m²), Surface pressure (Pa) ,Air temperature at 2m (K), Specific humidity at 2m (kg/kg), U-component wind at 10m (m/s), V-component wind at 10m (m/s)
