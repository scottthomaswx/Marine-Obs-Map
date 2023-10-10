# Marine-Obs-Map
This application allows the user to obtain buoy and land based meteorological station data from the National Data Buoy Center NDBC. The user can then select what variables they wish to see including wind speed and gusts colored by marine hazard product, wave height colored by height thresholds, station pressure, water temperature, and air temperature. This displays on a map for any stations over an area.

Dependencies include: MatPlotLib, Siphon, Pandas, GeoPandas, MetPy, Cartopy

Developer: Scott Thomas (@ScottTGL1)

Note: Small Craft Advisory Thresholds In The Plot Are Calibrated To Great Lakes Levels. Thresholds Can Be Adjusted If The User Desires In Dataframe Query. Thresholds By Region In At: https://github.com/scottthomaswx/Marine-Obs-Map/blob/main/SCY_Thresholds

Note: Great Lakes Mid Lake Buoys (E.g. 45003, 45007, 45008) Only report waves intermitently. If they do not appear when plotting wave heights, it may be the most recent observation did not record waves. Check the last wave ob and whether the most recent reported a wave here: https://www.ndbc.noaa.gov/
