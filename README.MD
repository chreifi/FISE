The following serialEM scripts are used by the Jensen group to collect FISE tomography data:

1-Jensenlab_FISE.txt

2-Jensenlab_GetEucentricHeight.txt

3-Jensenlab_GetCalibrations.txt

To run:
1) Insert all 3 related/required scripts into serialEM.
2) Add targets to the Navigator. The first target picked in each map will be a calibration tilt-series.
3) In the FISE script, adjust user inputs according to your project.
4) Enable dose fractionation and set the correct frame rate for the Record parameter.
5) Choose a working directory and file name to save the frames.
6) Adjust file properties. Recommended file properties: unnormalized TIF with LZW compression.
7) Run FISE script. To batch collect, acquire nav items and run FISE script as primary task.

Note: Working directory must contain the ArrayTilt_angles.txt and ArrayTilt_defoci.txt for the script to work correctly!

