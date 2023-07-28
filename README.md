# Upper Cook Inlet Exclusive Economic Zone Sport Harvest

Fulfills data request to estimate sport fish harvest in the Upper Cook Inlet Exclusive Economic Zone.

The working directory for this repository is located at S:\\RTS\\Reimer\\UCI_EEZ.

There are two main results in this repository. An early attempt was made to estimate salmon harvest in the UCI EEZ (see email RE_UCI data request in the Northern Economics Data Request folder) but we were unable to find good documentation on the methods used. The general approach for the earlier analysis was to use Guide Logbook data to approximate a fraction of the SWHS estimate in UCI that was taken in the UCI EEZ. The file EEZ_match.RMD recreates the earlier analysis and calculates a similar estimate while drawing inference about the percentage of salmon harvest that occurs within the UCI EEZ form guide logbook data reported from smaller geographic area. This analysis seemed flawed as theguide logbook program had switched from asking salmon focused charter captains to switch from using groundfish statistical areas to salmon statistical areas in 2015 and that change seemed to influence the result. This analysis also used SWHS data North of Bluff Point to estimate the total harvest in the area while the UCI EEZ has a farther North Southern boundary, at Anchor Point, and significant harvest occurs between the two boundaries. The Excel files that support this analysis are:

-   "Copy of Miller - SC Salmon....xlxs": used to create a very rough approximation of the percentage of the harvest which occured in the UCI EEZ using guide logbook data from all of Cook Inlet.

-   "SC Salmon harvest by federal....xlxs": used to create a very rough approximation of the percentage of the harvest which occurred in the UCI EEZ using guide logbook data from Upper Cook Inlet.

-   "Boat_shore_salmon_harvest.20221221.xlsx": SWHS estimates from areas K and L.

-   "UCI_salmon_boatshore_20221222.xlsx": SWHS estiamtes from area P.

The file EEZ_salmon-harvest.RMD refines the approach while only providing estimates since 2015. In the revised approach we use guide logbook data to estimate both the magnitude of the harvest and the fraction that occurred in the UCI EEZ while relying on SWHS data only to estimate the ratio between guided and unguided harvest.The Excel files that support this analysis are:

-   "Reimer Salmon Harvest in stat areas....xlsx": Guide ogbook harvest reported North of Anchor point.

-   ""Reimer Cook Inlet Inshore....xlsx"": Guide logbook data used to estimate the proprtion of fish harvest gt 3 nm from shore.

-   "UCI_salmon_boatshore_20221222.xlsx": SWHS estimates used to estimate ratio between guided and unguided harvest in UCI.

Files/folders in the .gitignore are: and a couple of data request sent to Northern Economics, who was the contractor NOAA used to quantify the potential ramification of a sport fishery closure in the UCI EEZ. - doc_styles: The files in this folder can be used to control the output styles used when a Rmarkdown document is rendered to word. I can't recall why tI produced 3 templates but left them as they were so as not to break anything. It the analysis is revisited the new biometrican should clean this up.

-    .pdf versions of the maps

-   A folder of data requests sent to Northern Economics

    -   RE_UCI data request contains the the original analysis we recreated in EEZ_match.RMD.

    -   "RE Data Request for Saltwater..." and "Revised_DataTables....xlxs" is a data request fulfilled by the Guide Logbook program in the winter of 2022-23.

    -   "RE Sportfish EEZState..." and "Revised_DataTables....xlxs" is a data request fulfilled by the SWHS program in the winter of 2022-23.
