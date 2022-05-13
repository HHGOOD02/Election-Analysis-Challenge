# Election Analysis

## Project Overview
A Colorado Board of Elections employee has provided me with voting information in a recent Congressional election for auditing. The specific sets of information sought after in this audit are:

1. Total number of votes cast
2. Complete list of candidates who recieved votes
3. The percentage of votes each candidate won
4. The total number of votes each candidate won
5. The winner of the election based on popular vote

## Resources
- Data Source: election_results.csv
- Software: Python 3.9.7, Visual Studio Code 1.67.1

## Summary
- There were 369,711 votes cast in this election
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results received were:
  - Charles Casper Stockham received 23% of the vote with 85,213 votes total
  - Diana Degette received 73.8% of the vote with 272,892 votes total
  - Raymon Anthony Doane received 3.1% of the vote with 11,606 votes total
- The winner of the election was:
  - Diana DeGette with 73.8% of the vote, and 272,892 total votes

## Challenge Overview
In addition to the candidate-centric overview, I have also been asked to provide a summary of the Counties involved in the election. To this end, I have additionally summarized the following data criteria:

1. List of counties involved in this Congressional election
2. Number of votes / voter turnout per county
3. Overall percentage of total votes cast per county
4. Highest turnout county

This will serve to further validate the details of the election as a whole, and to provide additional insight into the nature of the recent election for those who may wish to do further exploratory analysis in future.

## Challenge Summary
My findings have indicated a number of interesting patterns:

- Denver county is enormously ahead in terms of voter turnout, generating 306,055 votes (82.8% of the overall total)
- Jefferson and Arapahoe counties are closer in voter turnout, with 10.5 and 6.7% of the total vote respectively (38,855 & 24,801 votes)
- If Denver county is significantly larger than Jefferson and Araphoe counties, this overwhelming control of the vote is within expectation

This program is also applicable to other elections, and with slight modifications it will prove extremely versatile. Listed are two use cases for further development of this auditing program:

- With the data to do so, only limited change would need to be introduced in order for the program to compute turnout percent (of the county, not of the vote count), which may be useful in determining optimum policy courses of action; but may also assist in driving voter engagement in future elections
- With a relatively minor series of additions to the code, information could be parsed from the data on which candidates are most favored in which counties, which may help analyze voting trends and desires for policy platforms of the future
