# simultaneous_density_cd
This repository contains the data from simulations and real data from Spire satellites for validation of algorithm developed to estimate atmospheric density and drag-coefficient simultaneously. The results are published in Space Weather. 

The different cases for the simulations contain the nominal densities, drag-coefficients, and estimates for both iterations as described below. Please refer to the paper for details on the cases. 

angle_velocity: angle of velocity vector with the body x-axis in the body-frame.
Cd_est_iteration1: estimated drag-coefficient time-series after iteration 1
Cd_est_iteration2: estimated drag-coefficient time-series after iteration 2
Cd_filter: nominal/initial drag-coefficient time-series assumed in the filter
Cd_true: true drag-coefficient time-series
density_est_iteration1: estimated density time-series after iteration 1
density_est_iteration2: estimated density time-series after iteration 2
density_filter: nominal density time-series assumed in the filter
density_true: true density time-series
true_trajectory: true positions and velocities of the satellite corresponding to time steps specified in time_jd 
time_jd: time of propagation in seconds of julian date 


The Spire data files contain the nominal densities, the estimated densities and the smoothed postfit residuals (positions and velocities w.r.t POD) along the orbit of Spire satellite, ID 83.
