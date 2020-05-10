# BLM-Rentals-Shapefile

This repository is contains code for an ad-hoc script used at my workplace 
to generate a filtered shapefile to help identify tracts from our master shapefile.
It will take a rental excel list and filter a mastershapefile.
Cleanup text functions will be used to avoid mismatches based on trivial reasons (whitespace, case sensitivity, erroneous special chars, etc)

Workflow:
My colleague will send a rental list each month with leases up for renewal. 
Leases will need to be evaluated on DrillingInfo.
Rental list will be imported as a data frame and will be used to filter the master shapefile

Files Needed:
1. BLM Rental List.xlsx
2. Master Shapefile - All Company Leases
3. Export to shapefile
