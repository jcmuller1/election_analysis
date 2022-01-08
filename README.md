# Election Analysis

## Overview of Election Audit

The purpose of this analysis was to determine the results of an election. This included tallying of total votes, breaking down number of votes by county, and determining the winner of the overall election. 

## Election Audit Results

[!results](resources/election_results.png)

- Total votes cast: 369,711
- Votes by County
	- Jefferson County: 38,855 (10.5% of total votes)
	- Denver County: 306,055 (82.8% of total votes)
	- Arapahoe County: 24,801 (6.7% of total votes)
- Denver County tallied the greatest number of votes in the precinct
- Votes by Candidate
	- Charles Casper Stockham: 85,213 (23.0% of total votes)
	- Diana DeGette: 272,892 (73.8% of total votes)
	- Raymon Anthony Doane: 11,606 (3.1% of total votes)
- The election was won by Diana DeGette, who garnered 272,892 votes (73.8% of total votes)

## Election Audit Summary

This script provides a quick and easy way to sort through a large number of votes during an election and provides useful information, such as voter turnout and election results. One way this code could be modified is by breaking down the results of votes within each county. For example, how many of the 306,055 votes in Denver county were claimed by the winning candidate? Did one county have more votes for one of the losing candidates? These questions could be answered using the current data and would simply require an extra step of analysis.

Another modification that would also require slightly more information from the election commission would be calculating the voter turnout for each county and the region as a whole in terms of percent of elegible voters that participated in the election. This would require knowing the population of eligible voters in each county, but given that information this would be an easy addition to the analysis. 