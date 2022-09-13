# Election_Analysis
# **Overview of Election Audit**
Upon completing the analysis regarding the winning candidates for the Colorado Board of Elections, I then analyzed the counties within this election. This analysis consists of procuring the voter turnout for each county, the percentage of votes from each county, and the county with the highest turnout. In order to accomplish this, I used many of the same methods previously used to determine the candidate information and winning candidates. 
# **Election Audit Results**
The results of this analysis displayed the voter turnout of each county, percentage of votes within each county and the county with the highest turnout. Along with the results for each county, this analysis will go through the results of each candidate and the winning candidate of this election.  In order to obtain these results, I had to create lists and dictionaries and implement the for and if functions. The for statement allowed me to analyze each row within the file given, and the if function allowed me to create narrowed lists and determine the vote counts for county and candidates. In order to print the statements with all the results, I used the .write function to be able to write into a specific file, then using the print(), I was able to print the statements needed onto that file. Upon completing these steps I was able to achieve the following results:

![Election Analysis Results](https://user-images.githubusercontent.com/111406957/190025169-84547b7b-cda9-4bba-802e-658b37eb587c.png)


**Amount of votes cast in this congressional election**
* The total amount of votes cast is : 369,711

**Number of votes along with percentage of total votes for each county**
* County Votes:
    - Jefferson: 10.5% (38,855 )
    - Denver: 82.8% (306,055)
    - Arapahoe: 6.7% (24,801) 

**County with Largest Amount of Votes**
* Denver has the most votes (306,055)

**Number of votes along with percentage of total votes for each candidate** 
* Candidate Votes
    - Charles Casper Stockham: 23.0% (85,213)
    - Diana DeGentte: 73.8% (272,892)
    - Raymon Anthony Doane: 3.1% (11,606)

**Winning Candidate and Votes Information** 
* Diana DeGette
    - Vote Count: 272,892
    - Percentage: 73.8%
# **Election Audit Summary**
This analysis provided an in-depth view into the candidate and county information for this election which is why the Colorado Board of Elections should implement these methods for all future elections. By simply being able to dissect and understand any election data that may be given, it allows the analyst to be able to use this script after changing the file the information is being exploited from, and changing the variables to a relevant name. For example, in order to analyze smaller elections, the variable “county” can be changed to “city” along with using the specific file path to achieve the same results.  

