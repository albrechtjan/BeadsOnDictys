The MATLAB .mat files in this folder contain the bead trajectories analyzed in the paper *"Likelihood-Based Heterogeneity Inference Reveals Non-Stationary Effects in Biohybrid Cell-Cargo Transport"* by Albrecht, Dautzenberg, Opper, Beta, and Großmann. 
There is one file for each of the 4 bead sizes:
- 29 um
- 46 um
- 61 um
- 100 um

Each of the files contains a structure `data_mult[colloid_size]` with three fields:
- `position`: contains the xy-position of the bead in pixels where 1.56 px = 1 um
- `time`: The time of the position in frames. 1 frame corresponds to 15 seconds.
- `dT`: The time between frames, which is as mentioned above 15 seconds.

The jupyter notebook provides code to load the data in python.
