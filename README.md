# Election Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. 2. Get a complete list of candidates who received votes.
3. 3. Calculate the total number of votes each candidate received.
4. 4 Calculate the percentage of votes each candidate won.
5. 5. Determne teh winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.5.1, Jupityr

## Summary
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- There were 3 countys involved showing votes in the following magnitude:
-   1: Jefferson (38,855)
-   2: Denver (306,055)
-   3: Arapahoe (24,801)
- It is observed that the Denver county had the largest number of votes.
- The candidates were:
-   Charles Casper Stockham
-   Diana DeGette
-   Raymon Anthony Doane
- The candidate results were:
-   Candidate 1 recieved 23.0% of the vote and 85,213 number of votes.
-   Candidate 2 recieved 73.8% of the vote and 272,892 number of votes.
-   Candidate 3 recieved 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
-   Candidate 2, who received recieving 73.8% of the vote.

## Election Audit Summary
The following script is an efficient and user-friendly method of counting votes electronically and summarizing the outcome both by voter and each county involved in the process.  This script can accept any voting result that is contained in a .csv file.  
![image](https://user-images.githubusercontent.com/19878877/150646853-48acec1f-cd63-4a95-85f3-e7e979a443cf.png)
Utilizing a URL instead of an internal PC path, the same Pandas library can import a URL address for efficient processing from voting results placed on a secured web server.
(pandas.read_csv(URL) )

Currently, the input must be in a three column form (Ballot, county, candidate) but with an input-based modification, the software could handle the output style from different locations.  This would require coding that would search the input for the columns that are a specific style recognizing names and column titles that correspond to the target information.  That being said, the output will still show "candidate" and "county" information exclusively.
![image](https://user-images.githubusercontent.com/19878877/150647018-782d94d7-572d-4f25-a577-513fdb4cfcfd.png)

All in all, the Python script will efficiently process and count voting results during election times.  It has the strong ability to visualize the results in a tabular form (Pandas library) or graphically through libraries such as Matplotlib.  This will greatly improve automation, employee/volunteer efficiency, and represtation of regional voting.
