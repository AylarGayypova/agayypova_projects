# agayypova_projects
## Welcome! This repository is mainly for my work on anisotropy. 

## Please find the descriptions of folders/files contained below: 
* Summer_Solar_Dipole Folder:
  - 1DProjAmplitude&Phase file contains the 1D projections of Amplitude from the solar dipole skymaps fitted into a cosine function. It also includes the projections with expected amplitudes of skymaps based on the Compton-Getting Effect.
  - ___**2dSolar_Dipole** _file contains the code that makes the residual solar dipole maps by taking the sidereal signal for each month and subtracting all the data from it. This helps isolate solar signal.
  - _**GIFofSolarDipole**_ the gif files that combines all the monthly solar dipole skymaps
  - **OrbitalSpeed** file contains the code that makes skymaps due to Compton-getting effect using Earth's barycentric velocity from astopy function of python
  - **DailySolarDipole** file contains the daily amplitude versus time plots, similar to monthly amplitude plots. It gives amplitudes from daily average residual solar dipole maps obtained by taking the average of each day in a year over the 12 years and subtracting from it all the data. 
  - **OldvsNew** file splits 12 years of data into two. For over the first half from 2011-2017, we take the average of each month over 6 years and subtract out all the data. Repeat the process for the second half 2017-2023, and compare the two to see if there is any time dependent/systematic differences.
