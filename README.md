# Script for Dry Deposition Velocity of Particles

Version of this script: v19  (last updated: 04/12/2020)

Author: Nuno Canha

# Goal of the script

This python script aims to calculate the dry deposition velocity of particles (m/s) for a certain particle size at a named wind speed, relying on the function created by Hoppel et al. (2005) for the calculation of the particle deposition for a uniform surface source in equilibrium. The script uses as input a weather database with the following data: timestamp, temperature, relative humidity and windspeed.

# Features of the present updates: 
- focused on selected bins, Weather data from B&B (2017) and improvement of calculation's description.
- testing the bin edges

# Reference
W.A. Hoppel, P.F. Caffrey, G.M. Frick, Particle deposition on water: Surface source versus upwind source, J. Geophys. Res. D Atmos. 110 (2005) 1–15. doi:10.1029/2004JD005148.
