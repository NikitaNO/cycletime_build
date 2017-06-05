## Synopsis

CycleTime is a Geotab add-in. It is created to calculate time of the vehicle's trip from one zone (CutBlock) to 
another zone (MillSite). CycleTime add-in unites same routes (from same CutBlocks to same MillSites) and calculate
needed info (all the stops) between the start and the end point of route using special rules

## Description

There is a constant RULENAMES. It is an array - first element - start point, second - end point, others - all needed 
rules for calculating other needed info. So it will be needed to change this constant and table headers to use it for
another goals. Also there is filterTable and filterRoutes methods which need to be changed for new filters