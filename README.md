# FishCheckR

**WDFW creel data QA/QC script**

FishCheckR is a Shiny script that runs QA/QC checks on creel data from the Freshwater Fisheries Monitoring program (FRFM).

> **Access:** FishCheckR is for WDFW employees with database access credentials only. A password is required to query the database and run the script.

## Getting started

1. Open the FishCheckR R project.
2. In R, open `FishCheckR.Rmd`.
3. Install all necessary packages.
   - Install `creelutils` with `devtools::install_github("wdfw-fp/creelutils")`.
   - This requires the `devtools` package and an installation of RTools.
   - Follow all instructions to set up your keychain.
4. Click the **Run Document** button.
5. Once the image loads, select the fishery (or fisheries) you want to clean and click **Load data** in the sidebar.

## Reviewing your data

- Open the **QA/QC Summary** for a tally of errors. Click a row to jump to that check.
- You can also use the **QA/QC** dropdown menus to go directly to a check.
- Columns in every table can be sorted and filtered.
- All QA/QC checks have hyperlinks in the creel_event_id column. You must be logged in to Fish Apps for these links to work
