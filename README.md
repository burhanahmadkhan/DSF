# DSF
Decision-support System for Forecaster
Currently for precipitation, it is a LAPSE RATE OVERHAULING MODEL for gridded outputs of raw GFS
〖𝐺𝐹𝑆𝑃𝐿𝑈𝑆〗_𝑃=𝑃_(〖𝑚𝑜𝑑𝑒𝑙〗_𝑔 )∙(1+((ℎ_(〖𝑚𝑜𝑑𝑒𝑙〗_𝑔 )−ℎ_(〖𝑟𝑒𝑓〗_𝑔 ))∙𝛾_𝑃∙0.01))             ∀ 𝑔∈𝑁  
In the above equation, 𝑃_(〖𝑚𝑜𝑑𝑒𝑙〗_𝑔 ) represents precipitation magnitude from the raw NCEP-GFS output at any particular grid, and 𝛾_𝑃 is the optimized representative precipitation lapse rate derived by Immerzeel et al., (2012).
The GFSPLUS uses the Smith Sandwell 1 arc minute topography and bathymetry data for more realistic representation of terrain features.
Works with OpenGrADS Software
The software system generates the following:
GFSPLUS daily precipitation forecast in .png format.
GFSPLUS digitized Quantitative data for maximum and average precipitation for six catchments of the Indus basin.
GFSPLUS comparison with the then-casted NASA’s GPM satellite 24 hours accumulated precipitation for a day earlier than the day of forecast.
GFS data archive of the precipitation variable in NetCDF Format.
Burhan Ahmad (Developer)
