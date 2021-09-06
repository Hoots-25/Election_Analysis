# Election_Analysis

## Project Overview

The purpose of this project was to help Seth and Tom analyze the results of their local election on behalf of the election commission. This project focused on the candiates, counties, and the votes for each.  The election commission has requested information regarding the voter turnout for each county, the percentage of votes from each county, and the county with the highest turnout.

## Election Audit Results
County relevant details were found using iterations and conditional statements. The results can be viewed in a [.txt file](/Analysis/election_analysis.txt). The breakdown of the results is shown below:

### Total Votes
* There were a total of 369,711 votes in this precinct election

### County Breakdown
* Jefferson County: Made up 10.5% of the total vote outcome with 38,855 votes
* Denver County: Made up 82.8% of the total vote outcome with 306,055 votes
* Arapahoe County: Made up 6.7% of the total vote outcome with 24,801 votes

### Largest County Vote 
* Denver County had the largest number of votes with 306,055 counted

### Candidate Breakdown
* Charles Casper Stockham: Made up 23.0% of the total vote outcome with 85,213 votes
* Diana DeGette: Made up 73.8% of the total vote outcome with 272,892 votes
* Raymon Anthony Doane: Made up 3.1% of the total vote outcome with 11,606 votes

### Popular Vote Winner 
* Diana DeGette was the clear winner of this election
    * Received 73.8% of the popular vote with 272,892 votes

## Election Audit Summary
The attached script can be used, with some modification, to analyze the results of any election. The current script is able to find candidates, counties, and the votes pertaining to each. This script is only specific to analyzing this particular election due to the input. 

A modification can me made using the function `input()` to allow the user to select the file to read and write to. The variable `file_to_load` would be dependent on user input. This would allow the election board to analyze any election.

A second modification to the script is to allow the user to `input()` the name and location of the output file. This would allow users to select the directory and name of the election result file. The `file_to_save` variable would be dependent on the user input. Giving the end user autonomy allows the script to be used for multiple elections.