# Election_Analysis

Project Overview
A Colorado Board of Elections employee has given me tasks to complete the election audit of a recent Congressional election. The data presented will represent the candidates and counties they ran in. An initial analysis of the candidates revealed the following information:
  1.	The total number of votes cast: 369,711
  2.	A complete list of candidates who received votes:
    a.	Charles Casper Stockham
    b.	Diana DeGette
    c.	Raymon Anthony Doane
  3.	Total number of votes each candidate received:
    a.	Stockham received a total of 85,213 votes,
    b.	DeGette received a total of 272,892 votes, and
    c.	Doane received a total of 11,606 votes.
4.	Percentage of votes each candidate won:
    a.	Stockham received a total of 23% of the votes,
    b.	DeGette received a total of 73.8% of the votes, and
    c.	Doane received a total of 3.1% of the votes.
  5.	Winner of the election based on popular vote: Diana DeGette

# Resources
•	Data Source: election_results.csv
•	Software: Python 3.6.1, Visual Studio Code 1.38.1

# Summary
The analysis of the election showed that:
The candidate were: Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane. The candidate results were:

   	Charles Casper Stockham received 23% of the vote and 85,213 number of the votes.
    Diana DeGette received 73.8% of the vote and 272,892 number of the votes.
    Raymon Anthony Doane received 3.1% of the vote and 11,606 number of the votes.

The Winer of the Election was Diana DeGette, who received 73.8% of the vote and 272,892 number of the votes:

# Challenge Overview
# Overview of the Election Audit
After a recent Congressional election, I have been tasked with an audit to analyze voter turnout. In the preliminary review analysis was done around the candidates who ran for office and the votes they each received with the outcome of a winner being elected. This analysis is one step further and will explore voter data. Data will be analyzed around voter turnout in the respective counties, to include the count and percentages who voted in each county and determining the county with the highest voter turnout. 

# Election Audit Results
The analysis on voter turnout was built upon the existing election analysis cvs file.  The voter turnout information was layered into the code in python interpreter on candidates. I set my variables as county_list and county_votes. Refer to the visual studio code for the detailed data and below is the outcome of the data:
-There were 369,711 votes case in the congressional election
-The votes were broken down into the following counties:
	-Jefferson: 10.5% of the voters, totaling 38,855 voters,
	-Denver: 82.8% of the votes, totaling 306,055 voters, and
	-Arapahoe: 6.7% of the voters, totaling 24.801 voters.
-The county with the largest number of voters is Denver as it represents 306,055 voters out of the total 369,711 voters, equaling 82.8% of the votes.
The candidate who won the election was Diana DeGette who had 272,892 votes, with a winning percentage of 73.8% of the votes. The below summary screen provides the overall analysis: 

![image](https://user-images.githubusercontent.com/106719954/178179367-22440077-ef4c-478a-b7b2-5b495ab703f1.png)

# Summary
This audit analysis provides a lot of information that could be used by the election commission in future elections. Some modifications to the code and it could be applied for any election. One example of how the script can be modified is to change the dictionaries to include different cites across Colorado or other states. For example, if we wanted to look at Northern California cities, we could look at voter data in San Francisco, Oakland and Berkely. Those are more densely populated cities, and it could be inferred the voter turnout would be higher. An interesting point with more modification to the code would be to look at what percentage of the voters that the winner in our analysis Diana got from each city. We know her overall vote count was 

