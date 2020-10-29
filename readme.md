Here I collect tools for simulations for Theseus. 

This includes exposure maps created by myself based on obssim run results, which are arguably more useful for us than what was previously circulated (fits files).
The difference is 

1) they are not created by digitizing the contour plots Lorenzo presented, but rather directly using obssim run results (RA/DEC as function of time)
2) only survey mode is considered (no GRBs), which is what matters when we are looking for long continuous periods covered by observations
3) they are created per instrument and use simplified approximation for the FOV for SXI and XGIS. I dont know what was assumed by Lorenzo, but I simply assumed circular FOV with radii of 23 deg for SXI (corresponds to 0.5sr), and 5.25 and 38.5 deg for XGIS fully coded and half coded fields of view. The units are ks/day average throughout the survey as before. 


There is also an interactive (via binder) notebook which you can use to get some info for a particular source.
To do that, click on the binder link below, wait a bit (or a long time) and change source name and instrument in In[2] field.
After that re-run the entire notebook to update plots numbers
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/git/https%3A%2F%2Fgithub.com%2Fdoroshv%2Ftheseus/main?filepath=example.ipynb)
