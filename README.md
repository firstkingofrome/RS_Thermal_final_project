# RS_Thermal_final_project
Contains my workflow for the remote sensing thermal project spring 2022:


The Note book getTemperatureAtMargret.ipynb computes thermal surface temperatures near the margret weather station on the ross ice shelf and compares these values to those recorded by the weatherstation. This allows me to determine the approximate distribution of the error in surface temperature measurement. I assume that the errors for surface temperatures will follow the same distribution 125 km away at seismic station RS09 (this may not actually be true). This notebook can be run in collabratory, however a google earth engine API key is required.


The notebook getTempRS09.ipynb evaluates the surface temperature at the seismic station RS09 over a 1km^2 buffer. The surface temperature is then compared to the # of cryoseismic events which occured in the preceeding 12 hours (I slected this time window since the shelf flexes and cracks as the tide changes and I wanted the window to be large enough to capture this part of the tidal cycle). This note book also runs in collabratory (and also requires an earth engine API key)
