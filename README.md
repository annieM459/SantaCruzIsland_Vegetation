# SantaCruzIsland_Vegetation
Vegetation cover dataset from Santa Cruz Island spanning 1991-1995, 1998, and 2022.

## Description of the data and file structure

### Data Description

This dataset contains vegetation cover data collected from Santa Cruz Island, California, spanning multiple years (1991-1995, 1998, and 2022). The data include species composition, cover values, and substrate cover (bare ground and litter) across 100 permanent plots. The study was designed to monitor long-term changes in plant communities, particularly in response to historical grazing impacts, climate variability, and ecological succession. The dataset can be used to analyze shifts in vegetation structure, functional plant groups, and overall ecosystem changes over time.

### Methods

Between spring 1991-1995 and 1998, Klinger et al. (2002) estimated the density of woody species, the cover of all plant species, and substrate cover (bare ground and litter) within vegetation plots. Woody species were counted individually within each plot. Cover was estimated using a point-intercept method, where a point was extended vertically above and below 100 evenly spaced points (30 cm apart) along a central 30-meter line within each plot. All species intercepted by the point were recorded (Bonham 1989).

No data were collected between 1998 and 2022. In mid-March 2022, we resampled all 100 plots using the same methods established in the 1990s to ensure consistency and comparability across time periods.

### Files and variables

File: SantaCruzIsland_CoverData_91-95_98_22_Meeder.xlsx
Description: Primary dataset containing vegetation cover data from 1991-1995, 1998, and 2022.

### Variables
Acronym: Plant species code.
Plot: Unique identifier for vegetation survey plots.
Year: Year of data collection.
Plotcode: Combination of plot number and year.
Cover (%): Vegetation cover percentage.
Native (T/F/U): Indicates whether the species is native (T), non-native (F), or unknown (U).
Guild: Functional group classification (e.g., Grass, Shrub, Bare Ground).
Lifecycle: Growth form classification (e.g., Annual, Perennial, Shrub).
Category: Further classification of plant functional groups.
Slope (degrees): Slope of the plot location.
Aspect (degrees): Aspect direction of the plot.
Aspectcos: Cosine-transformed aspect value.
TRI (unitless): Topographic Ruggedness Index, a measure of terrain variability.
Vegline: Vegetation community type.
Status: Survey completion status.
Pasture: Historical grazing area designation.
Sheep Grazing & Cattle Grazing: Qualitative assessment of past grazing intensity (e.g., Low, Medium, High).
n: Sample size indicator.

### Missing Values

Missing values are represented as blank cells or "NA" where applicable.
