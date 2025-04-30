## Astronomy 416 Final Project
Brooke Kotten, bkotten@umich.edu
April 30, 2025


This project's underlying goal is to predict the decay of a solar flare. Flare decay can be important to model for scientific studies, but in this case, we want to model the decay for other purposes. I use linear regression and find two acceptable techniques for modeling flare decay.

Contents:
* astro 465 create flare list.ipynb: Jupyter Notebook of analysis
* sci_xrsf-l2-avg1m_g18_s20220902_e20250329_v2-2-0.nc: NetCDF of GOES-18 XRS Average One Minute Data
* sci_xrsf-l2-flsum_g18_s20220905_e20250329_v2-2-0.nc: NetCDF of GOES-18 XRS Flare Summary File

The most up to date average 1-m data is found at https://data.ngdc.noaa.gov/platforms/solar-space-observing-satellites/goes/goes18/l2/data/xrsf-l2-avg1m_science/

The most up to date flare summary file is found at https://data.ngdc.noaa.gov/platforms/solar-space-observing-satellites/goes/goes18/l2/data/xrsf-l2-flsum_science/

Readmes for XRS data are under the L2 tab at https://www.ncei.noaa.gov/products/goes-r-extreme-ultraviolet-xray-irradiance 