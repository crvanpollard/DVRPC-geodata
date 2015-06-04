# Mercer County Bicycle Level of Service (BLOS)

### Summary
Bikeability Scores for Mercer County roadways using the Bicycle Level of Service (BLOS) model, which generates a BLOS grade for any roadway based on the above factors (and others).

For more information please visit: http://www.dvrpc.org/asp/bikemercer/
and
http://www.dvrpc.org/Transportation/BicyclePedestrian/bicycle.htm.

### Data Development

For details on the BLOS model and our method of analysis for the scores you see on the Mercer County Bikeability Map, please visit: http://www.dvrpc.org/asp/bikemercer/pdf/process.pdf .

### Key Attribute Fields (Source)
`SRI`  Standard Route Identifier (NJDOT) –unique ID for each roadway

`MP_START`  Starting milepost of roadway (NJDOT)

`MP_END`  Ending milepost of roadway (NJDOT)

`HWY_TYPE`  Type of highway (0 Undivided, 1 Divided, 2 Dual/Dual) (NJDOT)

`LANES`  Lane count (NJDOT)

`PQI_MRM`  Pavement rating (not sure of exact meaning) (NJDOT, legacy data)

`PDI_MRM`  Pavement rating (not sure of exact meaning) (NJDOT, legacy data)

`IRI`  International Roughness Index pavement rating (NJDOT, legacy data)

`PAV_WD`  Pavement width on roadway (NJDOT)

`SHLD_WD`  Shoulder width (NJDOT)

`SPEED`  Roadway speed (NJDOT)

`AADT_AVG` Annual Average Daily Traffic

`AREA_TYPE` 

`FUNCCLS` Functional classification (NJDOT) codes don’t match the new ones

`SEG_MILES` Length of segment in miles

`OSP_PCT` On-street parking percentage

`STATUS`

`HV` Percent of heavy vehicles in traffic mix (Populated by functional class using DVRPC average regional values for “heavy trucks” plus buses. Data was provided by DVRPC modeling staff, and is derived from traffic counts and travel surveys over time). 

`WT` Combined width of outside lane and shoulder

`SCORE`

`BLOS`

`BIKESCORE` Final 

`ROADTYPE` Roadway designation for cartographic purposes

`EDITS`

#### Bikescore Lookup

`Excellent`  These major road segments are generally comfortable to bike along (BLOS grades A and B)

`Fair`  These major road segments may present some issues, depending on your experience level (BLOS grades C and D) 

`Unfavorable`  These major road segments are generally not comfortable to bike along (BLOS grades E and F) 

`Unbikeable`  Roadways on which bicycles cannot travel (limited access highways, highway access ramps and other selected “hazardous” routes)

`Minor_Fav`  These minor road segments are generally comfortable to bike along (BLOS grades A, B, or C) 

`Minor_UnFav`  These road segments are generally not comfortable to bike along (BLOS grades D, E, or F)

#### FC Attribute Lookup

01 RURAL PRINCIPLE ARTERIAL INTERSTATE

02 RURAL PRINCIPLE ARTERIAL OTHER

06 RURAL MINOR ARTERIAL

07 RURAL MAJOR COLLECTOR

08 RURAL MINOR COLLECTOR

09 RURAL LOCAL

11 URBAN PRINCIPLE ARTERIAL INTERSTATE

12 URBAN PRINCIPLE ARTERIAL OTHER FREEWAYS

14 URBAN OTHER PRINCIPLE ARTERIAL

16 URBAN MINOR ARTERIAL

17 URBAN COLLECTOR

19 URBAN LOCAL

99 RAMP

### Credits
DVRPC, 2015.

### Use Limitations
The Delaware Valley Regional Planning Commission (DVRPC) makes no warranty, representation, or guarantee as to the content, sequence, accuracy, timeliness, or completeness of any of the spatial data or database information provided herein. DVRPC and partner state, local, and other agencies shall assume no liability for errors, omissions, or inaccuracies in the information provided regardless of how caused; or any decision made or action taken or not taken by any person relying on any information or data furnished within. 