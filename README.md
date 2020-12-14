# Script for Dry Deposition Velocity of Particles

Version of this script: v19  (last updated: 04/12/2020)

Author: Nuno Canha

# Goal of the script

This python script aims to calculate the dry deposition velocity of particles (m/s) for a certain particle size at a named wind speed, relying on the function created by Hoppel et al. (2005) for the calculation of the particle deposition for a uniform surface source in equilibrium. The script uses as input a weather database with the following data: timestamp, temperature, relative humidity and windspeed.

# Output of the script:
This script provides 8 different figures (from time series of weather parameters, dry deposition of particles with diameter of 2.55 and 10 micrometers, and a summary of dry deposition velocities for integrated bins.
- Input data file: "BB_Hourly_correct.csv" (csv file with weather parameters averaged to 1 hour)

# Features of the present update: 
- focused on selected bins, Weather data from B&B (2017) and improvement of calculation's description.
- testing the bin edges

# Reference
W.A. Hoppel, P.F. Caffrey, G.M. Frick, Particle deposition on water: Surface source versus upwind source, J. Geophys. Res. D Atmos. 110 (2005) 1–15. doi:10.1029/2004JD005148.
