# Election Audit

## Overview

The puprose of this project was to create a python code to analyze the results of the election.
The data from the election was provided in a csv file. 

## Election Audit Results

**In the election, a total of 369,711 votes were cast from the 3 counties.**

### Vote Breakdown by County
- Denver: 306,055 Votes (82.8% of all votes collected)
- Jefferson: 38,855 Votes (10.5% of all votes collected)
- Arapahoe: 24,801 Votes (6.7% of all votes collected)

**County with largest voter turnout: Denver**

### Vote Breakdown by Candidate
- Diana DeGette: 272,892 Votes (73.8% of all votes)
- Charles Casper Stockham: 85,213 Votes (23.0% of all votes)
- Raymon Anthony Doane: 11,606 Votes (3.1% of all votes)

#### Winning candidate of election: Diana DeGette, with 272,892 votes, or 73.8% of total votes

## Election Audit Summary

Going forward, this code can be a great tool to analyze future election results. The code may need to be modified slightly depending on how the data is recorded in the csv file. For example, if the candidate name or county name is recorded in a different column, you would need to adjust to code to reflect the correct column.

        # Get the candidate name from each row.
        candidate_name = row[*insert number here*]

        # 3: Extract the county name from each row.
        county_name = row[*insert number here*]

If you were analyzing results by something other than county, for example state, you would need to change every mention of "county" in the code to reflect the proper term (e.g. state, city)
