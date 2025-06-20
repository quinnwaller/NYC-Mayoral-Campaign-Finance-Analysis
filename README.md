# NYC-Mayoral-Campaign-Finance-Analysis

Analysis of campaign finance contribitions to Cuomo, Mamdani, and Lander Mayoral campaigns, with data collected 6/20/25. 
This repository contains data, analytic code, and findings that support portions of the article, “Mamdani Outpaces Rivals in Out-of-State Donors to Mayoral Campaign,” published June 20, 2025. 


## Data
This analysis uses 3 spreadsheets.

The spreadsheets come from the following sources:

New York City Campaign Finance Board: 

"Cuomo data 6.20.csv": Raw data of campaign contributions to Andrew Cuomo

"Mamdani data 6.20.csv": Raw data of campaign contributions to Zohran Mamdani

"Mamdani data 6.20.csv": Raw data of campaign contributions to Brad Lander

You can download all the data [here](https://www.nyccfb.info/FTMSearch/Home/FTMSearch)

Each of the spreadsheets contain, among others, the following columns relevant to the analysis:

STATE — the state where the donor lives

AMNT - the amount of the donation

REFNO - the individual reference number for the donation


## Methodology
The notebook "campaign finance analysis.ipynb" performs the following analyses:

Part 1: Finding the total amount of funds raised/

Part 2: Filtering out donations from donors that live in New York

Part 3: Finding the average amount and total amount of non-New York donations

Part 4: Creating a new index that only contains the amount and number of non-New York donations by state, including Puerto Rico and Washington DC. 

Part 5: Renaming the "REFNO" column to "number of donations" for clarity

Part 6: Combining the analysis of Cuomo, Mamdani, and Lander's non-New York donors into one new index, with columns: "State", "Mamdani number of donations," "Lander number of donations" and "Cuomo number of donations"


## Outputs
The notebooks output this spreadsheet which contains [candidates_merged.6.20.csv]: (output/candidates_merged.6.20.csv.)

## Running the analysis yourself
You can run the analysis yourself. To do so, you'll need the following installed on your computer:

Python 3

The Python libraries specified in requirements.txt


## Licensing
All code in this repository is available under the MIT License. The data file in the output/ directory is available under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. All files in the data/ directory are released into the public domain.


## Feedback / Questions?
Contact Quinn at quinnwaller@gmail.com 
