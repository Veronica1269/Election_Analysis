# Election Analysis for the Colorado Board of Elections





## Overview


The purpose of this project is to complete an election audit for the Colorado Board of Elections. The following tasks are to be included in the completed election audit. Tasks 1 to 5  has been completed in Module 3. However, the election commission has requested some additional data for the audit. Tasks 6, 7 and 8 will be completed in this project using Python script. The results of audit will be printed in the command line and saved into file "election_results.txt"


1. Calculate the total number of votes cast. 
2. Get a complete list of candidates who received votes. 
3. Calculate the total number of votes each candidate received. 
4. Calculate the percentage of votes each candidate won. 
5. Determine the winner of the election based on popular vote. 
6. Determine the voter turnout for each county
7. Calculate the percentage of votes from each county out of the total count
8. Determine the county with the highest turnout





## Results


  - Total Votes: 369,711

The number of total votes is counted by a for loop go through each row in the "election-results.csv" file:





  - The number of votes and the percentage of total votes for each county in the precinct is:
      - Jefferson: 10.5% (38,855)
      - Denver: 82.8% (306,055)
      - Arapahoe: 6.7% (24,801)

The votes for each county are determined using a if statement as following:






  - Denver has the largest number of votes (306,055), which is over 82% of the total votes.
 
The percentage of each county is calculated by the following equation:
 





  - The breakdown of the number of votes and the percentage of the total votes each candidate received is:
      - Charles Casper Stockham: 23.0% (85,213)
      - Diana DeGette: 73.8% (272,892)
      - Raymon Anthony Doane: 3.1% (11,606)

The votes for each candidate are counted by the same method as the votes for each county. The name of three candidates are extracted using a if statement:





  - The winner of this election is Diana DeGette. She received 272,892 votes in total, which is more than 73% of the total votes.

The winning candidate's name and results is saved into text file as below:







## Summary


In this election audit, we analyzed the total votes for each candidate and the total votes for each county using a Python script. This dataset was limited and only included 3 counties and 3 candidates. However, if election results were available for more counties or more candidates, the same loops can still be applied to go through the dataset. 


To be better adapted for any election outcome, the relation between candidates and counties should be explored as well. In addition to the winning candidatein the election, the script can be modified to determine the winning candidate in each county as well. It can also be modified to make a breakdown of the number of votes and the percentage of the total votes each candidate received in each county.



