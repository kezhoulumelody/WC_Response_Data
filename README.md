# WC_Response_Data
Data for GRL paper: Mechanisms of Fast Walker Circulation Responses to CO2 Forcing.
This repository consists all the data mentioned in the paper.
The data is in NetCDF format, which can be accessed via tools like ncdump, cdo, grads. It can also be read via Python and Matlab once you import the NetCDF modules.
The naming convecntions are: var_group_time_temporal-average_regional-average.nc (for example: thetao_CMIP5-WG_f6yrs_mon-mean_5S-5N-mean.nc).
The variables are: ts(surface temperature), thetao(ocean potential temperature), omega(vertical pressure velocity), u(zonal wind) and v(metidional wind).
The groups are: CESM1-LE, CMIP5-CG and CMIP5-WG.
time_temporal-average includes: f2yrs_mon-mean(monthly output of the first 2 years), f6yrs_mon-mean(monthly output of the first 6 years) and l30yrs-mean (average of the last 30 years).
regional-average includes: 5S-5N-mean(meridional mean over 5S-5N).
