# Election Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate teh total number of votes cast.
2. 2. Get a complete list of candidates who received votes.
3. 3. Calculate the total number of votes each candidate received.
4. 4 Calculate the percentage of votes each candidate won.
5. 5. Determne teh winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.5.1, Jupityr

## Summary
The analysis of the election show that:
- There were "x" votes cast in the election.
- There were 3 countys involved showing votes in the following magnituge:
-   1
-   2
-   3
- It is observed that the xxx county had the largest number of votes
- The candidates were:
-   Candidate 1
-   Candidate 2 
-   Candidate 3
- The candidate results were:
-   Candidate 1 recieved x% of the vote and "y" number of votes.
-   Candidate 2 recieved x% of the vote and "y" number of votes.
-   Candidate 3 recieved x% of the vote and "y" number of votes.
- The winner of teh election was:
-   Candidate x, who received recieved x% of the vote and "y" number of votes.

## Election Audit Summary
The following script is an efficient and user-friendly method of counting votes electronically and summarizing the outcome both by voter and each county involved in the process.  This script can accept any voting result that is contained in a .csv file.  Currently, the input must be in a three column form (Ballot, county, candidate) but with an input-based modification, the software could handle the output style from different locations.  That being said, the output will still show "candidate" and "county" information exclusively.
