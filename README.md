# EPS 88: A Python Introduction to Earth Science

## Introduction

Course materials for the Data Science connector course **PyEarth: A Python Introduction to Earth Science** being taught in the Earth and Planetary Science Department at UC Berkeley in Spring 2023 by Nick Swanson-Hysell (https://github.com/Swanson-Hysell).

If you have a UC Berkeley account, you can launch these materials on Datahub using this link: https://datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fds-connectors%2FEPS88-Spring-2023&urlpath=tree%2FEPS88-Spring-2023%2F

## License

The contents of this repository are licensed for reuse under a [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](http://creativecommons.org/licenses/by-nc/4.0/) license.

## Schedule

| Meeting Date | Topic | Learning objective | Technical skills |
| --- | --- | --- | --- |
| Week 1 : Jan 23 | What is your birthquake? | Be introduced to using the Jupyter notebook environment and using it to access and inspect data. | *Defining variables and accessing tabular data through an API.* Use Python code within a Jupyter notebook to access an online API to pull in and inspect tabular data using `pandas`. |
| Week 1 assignment | Maps | Develop an understanding of map projections and visualizations of geospatial data. | *Map generation.* Learn to generate maps using `cartopy` using different projections and to plot locations. |
| Week 2 : Jan 30 | Earth's continents and oceans | Compare the distribution of Earth's topography (hypsometry) to a normal distribution. Explain the distribution in terms of continental crust vs. oceanic crust density. | *Simple statistics and data visualization.* Use `numpy` to load data and do simple statistical calculations such as `np.mean`. Use the `matplotlib` to visualize distributions of data as histograms and cumulative distributions. |
| Week 2 assignment | Seafloor age and plate tectonics | Use global seafloor age distribution to make inferences about plate tectonic processes. | *Tabular data wrangling and visualization.* Get further introduced to the `pandas` library. Use `cartopy` functions to visualize geospatial data in order to identify patterns. |
| Week 3 : Feb 6??| Global earthquakes and plate tectonics??|??Illuminate plate boundaries by plotting global earthquakes. Visualize a subducting plate by examining earthquakes in the Andes.??|??*Data wrangling and visualization.* Continue use of the `pandas` library as well as `matplotlib` and `cartopy` functions. |
| Week 3 assignment??|??Global earthquakes and seismograph interpretation??|??Make connections between earthquake magnitude/depth and plate boundary type. Analyze a seismograph and relate differential wave travel times to distance using established time-travel curves.??|??*Continued data wrangling and visualization; calculations.* Continued use of the `pandas` library as well as `matplotlib` and `cartopy` functions to visualize data. Use Python to make calculations related to Earthquake distance.??|
| Week 4 : Feb 13 |??Seafloor spreading and crustal magnetism??|??Use bathymetry data in combination with marine magnetic anomaly data to evaluate seafloor spreading. Interpret the distance from the spreading ridge where the last geomagnetic reversal happened across different spreading ridges and use this distance to calculate spreading rate.??|??*Data filtering and detrending* Indexing, filtering and cleaning data using `pandas`. Declare a function to detrend and filter magnetic anomaly data.??|
| Week 4 assignment |??Seafloor spreading | Use expanded age pick data sets from multiple ocean basins and determine seafloor spreading rates through applying linear regression.??|??*Correlation and regression* Use the `numpy` `polyfit` function to develop linear least-squares regressions for data and the `polyval` data to use these regressions to model a process for two sets of measurements. Use the `scipy` `stats.linregress` function to calculate related summary parameters. |??
| Week 5 : Feb 20 |	No class (President's Day)	|??	??
| Week 6 : Feb 27	|??Probabilities applied to Earth and planetary processes |??Discuss different statistical distributions and the concepts of theoretical versus empirical distributions. Consider probability distributions applied to meteor showers and earthquake occurence and the geomagnetic field . ??|??*Monte Carlo simulation* Use the module `numpy.random` to generate examples of simulated data sets.
| Week 6 assignment	| Earth's reversing magnetic field | Earth's geomagnetic polarity timescale. Consider the time series of geomagnetic reversals and how reversal frequency could be represented with probability distributions. | Implement additional probability distributions using `scipy` including the gamma distribution |
| Week 7 : March 6	|??Ice sheets??|	Use directional data to make inferences about flow directions of the Cordillera ice sheet | *Bootstrap resampling* Utilize bootstrap resampling as a means make inferences about data.??|
| Week 7 assignment	| Bay Area wind??| Gain insight into Bay Area climatology as a function of season through analysis of hourly wind data at SFO | *Apply the bootstrap percentile method* Utilize bootstrap resampling to develop estimates of the 95% confidence interval associated with statistical summary parameters.??|
| Week 8 : March 13	|??The age of the universe and the age of the Earth??| Use the retreat velocity of galaxies and supernova as a function of their distance to gain insight into the Hubble constant and the age of the universe | *Regression* Determining regression lines through least squares to gain insight into data and enable prediction  ??
| Week 8 assignment??|??Atmospheric CO<sub>2</sub>??|??Use the Mauna Loa Observatory atmospheric carbon dioxide concentration data set to quantify the rate of CO<sub>2</sub> rise over the past 60 years.??Compare trends inferred from regression to RCP emission scenarios | *Regression* Assess residuals in order to evaluate regressions. Use regression models for prediction.  
| Week 9 : March 20	| Ice core paleoclimate archives |??Determining rate of change of atmospheric CO<sub>2</sub> levels from merged ice core data sets | 	*Data wrangling* Gain experience wrangling data from different formats for analysis. Get set-up with a local Python installation.
| Week 9 assignment | Ice core CO<sub>2</sub> | Compare rates of change in the ice core and Mauna Loa CO<sub>2</sub> datasets |	*LOWESS* Apply locally weighted scatterplot smoothing using the `scipy` `statsmodels` in order to develop non-parametric fits to data. Use these fits to gain insight into rates of change.
| March 27 |??No class ??? Spring Break	??	
| Week 10 : April 3	|??Glacial-interglacial cycles | Investigate time series data to gain insight into the drivers of glacial-interglacial cycles | *Conduct spectral analysis* Use tools within the `scipy` package in order to calculate power spectral density from time series data |
| Week 10 assignment	|??Paleoclimate proxies and the mid-Pleistocene transition |
| Week 11 : April 10	|??Lava flow geochemistry |
| Week 11 assignment	|??
| Week 12 : April 17	|??Tectonic setting of volcanos | Machine learning of volcanic setting
| Week 12 assignment	|
| Week 13 : April 24	|??Geodetic data | Review concepts while analyzing a GPS data set |
| Week 13 assignment	| Final project plan |
| Finals week	|??Presentations on final projects during exam period??|
