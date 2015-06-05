# CyclePhilly

### Summary
These datasets reflect CyclePhilly trips that were mappable to DVRPC's Open Street Map facility network from May through October, 2014 (6 months; 8,340 individual trips by 220 unique CyclePhilly users). CyclePhilly trip data was processed and snapped to the nearest road or trail segment using a special algorithm so that total volumes by segment could be calculated and compared (some facilities--particularly park trails--may not be in the mapped network; CyclePhilly data for these segments is not shown). 

Note that the CyclePhilly trips do not reflect all bicycling in the city and region; CyclePhilly users' trip patterns may not reflect those of all cyclists. Trip ends (origin/destination) have been 'fuzzed' to protect users' privacy, so true start and stop locations are obscured in these datasets. A data dictionary and ReadMe are included within each ZIP file.

For more information about the data visit: http://www.dvrpc.org/webmaps/CyclePhilly/.

Go get the CyclePhilly App! : www.cyclephilly.org

### Go Get the Data here!
http://www.dvrpc.org/webmaps/CyclePhilly/

Found under the 'Tools and Data' dropdown menu

Datasets are broken into several different categories and formats (Shapefile and GeoJson)

- Trip detail by segment: Discrete trip data for each segment in the network

- Trip by trip summary: Line work for individual CyclePhilly trips

- Trip purpose summary by segment: Aggregated/summarized data for each segment in the network

- Segment network nodes: Can be used with the above datasets to support spatial analysis

### Data Development

To be used for planning purposes

### Key Attribue Fields
Field Name	Description	(Source)

`LINKNO` 	Unique Link Value from OSM network 	(OSM)

`LinkName` 	Road name 	(OSM)

`TTRIPS` 	Totals Trips - All purposes 	(CyclePhilly)

`COTRIPS` 	commute trip 	(CyclePhilly)

`ERTRIPS` 	errand trip 	(CyclePhilly)

`EXTRIPS`	exercise trip 	(CyclePhilly)

`OTTRIPS` 	other trip 	(CyclePhilly)

`SCTRIPS` 	school trip 	(CyclePhilly)

`SHTRIPS` 	shopping trip 	(CyclePhilly)

`SOTRIPS` 	social trip 	(CyclePhilly)

`WOTRIPS` 	work-related trip 	(CyclePhilly)

### Credits
CyclePhilly, OSM, DVRPC, 2015.

### Use Limitations
The Delaware Valley Regional Planning Commission (DVRPC) makes no warranty, representation, or guarantee as to the content, sequence, accuracy, timeliness, or completeness of any of the spatial data or database information provided herein. DVRPC and partner state, local, and other agencies shall assume no liability for errors, omissions, or inaccuracies in the information provided regardless of how caused; or any decision made or action taken or not taken by any person relying on any information or data furnished within. 