# FishCheckR 
# WDFW creel data QA/QC script
FishCheckR is a Shiny script that runs QA/QC checks on creel data from the Freshwater Fisheries Monitoring program (FRFM). 
For use by WDFW employees with database access credentials only. Password is required to query the database and run the script. 
# To use: 
1- Open the FishCheckR R project
2- In R, open the FishCheckR .RMD
3- Install all necesary Packages
  To install creelutils, use this script: devtools::install_github("wdfw-fp/creelutils")
  this currently requires the devtools package and an installation of RTools
4- Click on the "Run Document" button 
5- You may need to move the Shiny window to find the password entry window 
6- Connect to the database using your password. 
  If the password doesn't work, you may need to add your credentials to the "config.yml" file
7- Once the image loads (usually a few minutes), use the menu dropdowns to check the data.
  Columns can be sorted and filtered
