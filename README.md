# FiSL-Reburn


# Data 
https://www.sciencebase.gov/catalog/item/546e6655e4b0fc7976e4e89e

Caveats of Land surface temperature from Landsat https://www.usgs.gov/landsat-missions/landsat-collection-2-surface-temperature

Modis albedo product https://www.umb.edu/spectralmass/v006/mcd43a3-albedo-product/#:~:text=Black%2Dsky%20albedo%20(directional%20hemispherical,the%20diffuse%20component%20is%20isotropic.

Landsat Collection 2 Surface Temperature https://www.usgs.gov/landsat-missions/landsat-collection-2-surface-temperature

Arset EE code for LST https://appliedsciences.nasa.gov/get-involved/training/english/arset-satellite-remote-sensing-measuring-urban-heat-islands-and

# Data Viz

https://r-graph-gallery.com/color-palette-finder
#FED789FF, #023743FF, #72874EFF, #476F84FF, #A4BED5FF, #453947FF



# Notes 

Standard Time Since Fire (TSF) Bins:
Immediate (0 years) – The year of the fire event.
Short-Term (1–5 years) – Early post-fire recovery, dominated by pioneer species and rapid ecological changes.
Mid-Term (6–10 years) – Vegetation regrowth stabilizes, early successional species thrive.
Long-Term (11–20 years) – More stable ecosystem recovery, with gradual shifts in dominant vegetation.
Extended Recovery (21–30+ years) – Later successional stages, tree regrowth, and canopy closure in forested systems.


Alternative Groupings (Used in Some Studies):
0-1 years: Immediate fire effects.
2-5 years: Rapid post-fire changes.
6-15 years: Intermediate recovery phase.
16-30+ years: Long-term recovery.


# Scripts

1. `OrganizeFirePerimetersByYear.Rmd` Take MTBS and NBAC and save by fire year for AK and Canada.



# Analysis

## Decision Tree Classification

Multiply spectral indices were extract for for field sites, [see code]()
Multiple spectral indices were extracted for sampled points, [see code](https://code.earthengine.google.com/4277bc3be78bffa5a0d41a8a7b0a7d59). This is then used with the field model to predict burned/unburned
