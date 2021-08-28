# Taurus_Auriga
Python scripts and observe scripts prepared for SMA project, 2021A-A010. 
The observations purpose is to constrain the spectral indices of 47 Class II protoplanetary disks in Taurus-Auriga star forming region. 
The science targets were selected from Andrews & Williams (2005) by their flux densities to achieve > 10-sigma significance in < 2 hours observing time. <br /> <br />
File 'Target.txt' lists the target name, flux density at 0.85 mm, uncertainty, flux density at 1.3 mm, uncertainty measured by Andrews & Williams (2005). 
Python script 'plot.py' reads these flux density measurements and does 1.3 mm - 0.85 mm flux density scatter plot and their distributions. <br />
File 'Target_a.txt' lists the submillimeter spectral index (alpha), uncertainty of the selected targets fit by Andrews & Williams (2005). 
Python script 'plot1.py' reads spectral index and plot cummulative distribution of alpha for the 47 science targets. <br /> <br />
In the observing script, we want to minimize the path of observing 47 science targets and group them into 15 mins blocks with gain calibrator in the beginning and end. 
In a 1.5 hrs observing loop, we allocated 1.5 hrs to each target source according to the propotions of their estimated observing time in the proposal and converted the allocated time into number of scans with 15 secs in each scan. <br /> <br />
The icrs sky coordinate is obtained from Gaia Archive. 
File 'targetname_1.txt' lists the target name, RA, Dec, number of scans at 400 GHz, number of scans at 230 GHz in a 1.5 hrs loop. <br />
Jupyter notebook 'Coordinate.ipynb' contains 11 cells: <br /> 
The first cell plots the 

