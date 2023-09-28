# NASA Space Apps 2023 

<p align="center">
  <img src="https://github.com/jpmonteagudo28/NASA_SA23/blob/main/Space_Apps_Logo_White.png" width="350" title="hover text">
</p>


## The Challenge:  
Use the "raw" data from DSCOVR—faults and all—to predict geomagnetic storms on Earth. Currently, NOAA relies on stable, well-calibrated level 2 data for its forecasts. The challenge is to develop your own geomagnetic activity forecast using the raw DSCOVR data directly as input. When you are interpreting your results, think about what satellite operators, electrical utilities, the airline industry, the armed forces, and others need to consider when they are relying on a forecast from an aging instrument. It is important to be able to predict geomagnetic activity as quickly and accurately as possible.


### The Deep Space Climate Observatory (DSCOVR) 👾 🪐 🚀

DSCOVR ([Deep Space Climate Observatory](https://solarsystem.nasa.gov/missions/DSCOVR/in-depth/))  is an American space weather station that monitors changes in the solar wind, providing space weather alerts and forecasts for geomagnetic storms that could disrupt power grids, satellites, telecommunications, aviation, and GPS

When operating reliably, the National Oceanic and Atmospheric Administration’s (NOAA’s) space weather station, the Deep Space Climate Observatory (DSCOVR), can measure the strength and speed of the solar wind in space, which enables us to predict geomagnetic storms that can severely impact important systems like GPS and electrical power grids on Earth. DSCOVR, however, continues to operate past its expected lifetime and produces occasional faults that may themselves be indicators of space weather. Your challenge is to use the "raw" data from DSCOVR—faults and all—to predict geomagnetic storms on Earth.

#### What is Currently Measured by DSCOVR:

The DSCOVR Faraday Cup is the instrument that provides the solar wind density, speed, and temperature used by NOAA to run its forecast models. NOAA refers to the densities, speeds, and temperatures as "level 2" data. These quantities are not measured directly, however; the instrument actually measures the entire spectra of solar wind particles over time and then computes those quantities from the spectra. These spectral data are referred to as "level 1" data, or sometimes as "raw" data. 
To work well, a space science experiment must be stable and well-calibrated to translate the "raw" data into the more useful "level 2" data. DSCOVR no longer meets these criteria; in its old age, certain electrical anomalies and faults have been observed that shift the calibration and introduce noisy signals in unpredictable ways into DSCOVR raw data. When these faults occur, NOAA generally attempts to identify them and switches to a backup weather station rather than attempting to recalibrate or mitigate the error to produce the level 2 data accurately.



## Resources available to use
 1. WORKING DEMONSTRATION FOR READING DSCOVR EXPERIMENTAL DATA - [OMNI hourly Dataset](https://hpde.io/NASA/NumericalData/OMNI/PT1)
 2. [CARISMA FLUXMAGNETOMETER DATA](http://data.carisma.ca/FGM/) - Used to validate DSCOVR data(8 Hz) and a simple [format guide](https://www.carisma.ca/carisma-data/fgm-data-format)
 3. [CANADIAN SOLAR FLUX ARCHIVE (F10.7)](https://www.spaceweather.gc.ca/forecast-prevision/solar-solaire/solarflux/sx-5-en.php) - Data from the Canadian solar flux archive   

### Other Resources
NOAA Space Weather Prediction Center (specifically):  
     i. [Real Time Solar Wind](https://www.swpc.noaa.gov/products/real-time-solar-wind)  
     ii. [Geospace Magnetosphere Movies](https://www.swpc.noaa.gov/products/geospace-magnetosphere-movies)  
     iii. [3D Geomagnetic Forecast](https://www.swpc.noaa.gov/products/3-day-geomagnetic-forecast)  
     iv. [Planetary K-Index](https://www.swpc.noaa.gov/products/planetary-k-index)  
