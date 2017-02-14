### Dask Tryout

This repository is based on /DataExplorationTool. The driver classes in that repo have been rewritten using the dask library instead of pandas. Dask enables easy parallel computing and handles data sets that don't fit in memory.


##### To dos
* Look into mode() and median()
* Bivariate statistics: frequency tables, Chi-Squared, etc
* How to handle graphs with dask (sample? compute where possible?)
* Determine which operations can be done in-place versus making a new copy
* Try with larger and larger data sets to find the upper bound

