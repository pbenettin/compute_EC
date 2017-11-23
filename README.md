# compute_EC.pqi

This file can be used to compute the electrical conductivity of individual ion species in streamflow using the software phreeqc. The approach is described in:
[1] Benettin, P., & van Breukelen, B. M. (2017). Decomposing the Bulk Electrical Conductivity of Streamflow To Recover Individual Solute Concentrations at High Frequency. Environmental Science & Technology Letters, acs.estlett.7b00472. https://doi.org/10.1021/acs.estlett.7b00472

The file is extensively commented. An input ion concentration timeseries can be inserted by, e.g., pasting values from a spreadsheet table. For each point of the timeseries, phreeqc will compute the electrical conductivity of each ion species and the corresponding coefficients 'a' (see [1]).

The phreeqc software, with documentation and example files, is freely available at https://wwwbrr.cr.usgs.gov/projects/GWC_coupled/phreeqc/
