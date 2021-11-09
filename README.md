# Election Analysis

[Overview](#overview-of-election-audit)

[Resources](#resources)

[Election Audit Results](#election-audit-results)

[Summary](#summary)

## Overview of Election Audit 
Our client, the Colorado Board of Elections, has tasked us with auditing the results of a recent local congressional election.  The tasks performed in this process were:

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes, and the counties where those votes were cast.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. Calculate how many votes were received in each county, and their percentage of the total votes.
7. Determine which county had the largest voter turnout.

## Resources
- Data Source: [election_results.csv](https://github.com/ZeroDarkHardy/Election_Analysis/blob/main/Resources/election_results.csv)
- Python Code: [PyPoll_Challenge_starter_code.py](https://github.com/ZeroDarkHardy/Election_Analysis/blob/main/PyPoll_Challenge_starter_code.py)
- Software: Python 3.10.0, Visual Studio Code 1.62.0

## Election Audit Results
The full analytical review of the election results show:
- There were a total of 369,711 votes cast in the election.
- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:
    - Charles Casper Stockham received 23.0% of the total, with 85,213 votes.
    - Diana DeGette received 73.8% of the total, with 272,892 votes.
    - Raymon Anthony Doane received 3.1% of the total, with 11,606 votes.
- The winner of the election was:
    - Diana DeGette, who received 73.8% of the total votes, with 272,892 votes cast in her favor.
### Results by County
- Jefferson County: 10.5% of total votes cast (38,855)
- Denver County: 82.8% of total votes cast (306,055)
- Arapahoe: 6.7% of total votes cast (24,801)

- Denver county had the largest voter turnout, by far.

![READOUT GALLERY](https://github.com/ZeroDarkHardy/Election_Analysis/blob/main/Resources/readout_gallery.png)

## Summary
The elegant code we've compiled here has functionality that can handle massive amounts of data, far beyond this single election.  We'd like to propose using this code to handle all your future election analysis, as it can be given minor tweaks to process whatever voter data you have available. With more data, we can add processes to identify which age range the majority of each candidate's voters belong to, what percentage of voters did so by mail (if applicable), or even what economic group comprise the majority of a candidate's voter base.