# chapter-3-challenge

## Project Overview
A Colorado Board of Elections employee has given me the following tasks to complete the election audit of a recent local congressional election

1. Calculate the total number of votes cast.
2. Get the list of county where the votes were conducted
3. Calculate the total number of votes each county received
3. Calculate the percentage of votes each county received
4. Determine which is the county with the most votes
5. Get a complete list of candidates who received votes.
6. Calculate the total number of votes each candidate received.
7. Calculate the percentage of votes each candidate won.
8. Determine the winnder of the election absed on popular vote.

## Resources
- Data source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Election Results
The analysis of the election show that:
- There were "369,711" votes cast in the election
- The counties where the votes were casted were:
    - Jefferson
    - Denver
    - Arapahoe
- The county votes distribution were:
    - Jefferson: 10.5% with 85,213 votes
    - Denver: 73.8% with 306,055 votes
    - Arapahoe: 6.7% with 24,801 votes
- The county with the most votes:
    - Denver with 306,055 votes which takes up 73.8% of total votes
- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:
    - Charles Casper Stockham received "23.0%" of the vote and "85,213" number of votes.
    - Diana DeGette received "73.8%" of the vote and "272,892" number of votes.
    - Raymon Anthony Doane received "3.1%" and "11,606" number of votes.
- The winner of the election was:
    - Diana Degette, who received "73.8%" of the vote and "272,892" number of votes.

## Project Summary
From the code, we can see that it is very easy to expand the scope of work since it employes the same logic with most of the changes belong to the variables we are tracking. Therefore, we can apply this code to handle the analysis of any elections and modify the variables accordingly to the specific attributes we want to track in an election. For example:
- If we were to analyze the presidential election in the United States, we can modify the code to track the votes based on states instead of counties and keep the code regarding candidates the same. One small thing to note here is that we need to modify the index accordingly in case the data file's structured is changed regarding data columns.
- Another example is we can also modify the code so that it tracks the Senate results or the House results where there are only two contenders which are Democratic Party and Republican party.
