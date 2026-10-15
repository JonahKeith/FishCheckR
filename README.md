# FishCheckR 
# WDFW creel data QA/QC script
# FishCheckR is a Shiny script that runs QA/QC checks on creel data from the Freshwater Fisheries Monitoring program (FRFM). 
# For use by WDFW employees with database access credentials only. Password is required to query the database and run the script. 
# To use: 
# 1- Open the FishCheckR R project
# 2- In R, open the FishCheckR.RMD
# 3- Install all necesary Packages. To install creelutils, use this script: devtools::install_github("wdfw-fp/creelutils"). This currently requires the devtools package and an installation of RTools. Follow all instructions to set up keychain 
# 4- Click on the "Run Document" button 
# 5- Once the image loads, select the fishery(s) you want to clean and hit "load data" in the side bar. Open the QA/QC summary for a tally of errors, click on the row you want to see or use the QA/QC dropdowns to check the data. Columns can be sorted and filtered.
# 6- Nerd Out
