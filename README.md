# puf_irs_crosswalk

A project to develop correspondence between the 2015 Public Use File (PUF) data and published IRS aggregates so that we know which IRS spreadsheets and cells correspond to which variables on the PUF. This is important for developing targets for the TMD project.

The basic steps are to:

* For 2015
  * Choose a PUF concept
  * Get its 2015 IRS "Full SOI Sample" value from the PUF documentation
  * Find which IRS spreadsheets/cells contain the SAME value, or nearly so, making them likely equivalent concepts
  * Verify by comparing (1) the IRS form, line, and instructions for the PUF variable to (2) the IRS description of the spreadsheet values, by examining IRS Publication 1304.
* For later years
  * Track the concept in IRS spreadsheets for 2015 to corresponding spreadsheets in later years, especially 2022, and note any changes in concept definition or measurement
