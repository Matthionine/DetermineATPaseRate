# DetermineATPaseRate

This R notebook allows to determine the ATPase rate easily.
It uses an excel file with a sheet for the measurements 340, 900 and 1000nm ("NADH (340nm)", "TestWL (1000nm)", "RefWL (900nm)").
All sheets require a column for time, temp (optionally), and each sample (=well)
The latter two sheets (900 and 1000nm) are used for the path length correction and only need one measurment per run.
