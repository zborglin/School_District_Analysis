# School_District_Analysis
Python Application
Comprehensive Statistical Analysis of a DataFrame

## Project Overview
The dataset associated with 15 local schools became corrupted when administration officials detected fraudulent behavior from a subset of the DataFrame associated with Thomas High School. 

The contents related to the request: 
-An audit of school information and test scores
-Analysis of the audited school data and communication of any impacts associated with the DataFrame breach:

1. How is the test score by district summary affected? 
2. How is the test score by school summary affected?
3. How does removal of the compromised data affect Thomas High School's performance relative to the other schools?
4. How does removal of the compromised data affect Thomas High School's: math and reading scores by grade, scores by school spending per student, scores by school size, scores by school type.

## Resources
- Data Sources: students_complete.csv, schools_complete.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Summary
The analysis of the election show that:
- There were "369,711" votes cast in the election.
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received "23.0%" of the vote and "38,855" number of votes
  - Diana DeGette received "73.8%" of the vote and "272,892" number of votes
  - Raymon Anthony Doane received "3.1%" of the vote and "11,606" number of votes
- The winner of the election was:
  - Diana DeGette, who received "73.8%" of the vote and "272,892" number of votes.
- Here is the txt file output that may be used cross-platform:
#
![PyPoll Election Analysis Algorithm: Txt File Output](https://github.com/zborglin/Election_Analysis/blob/main/analysis/election_results_output.png)
#

## Challenge Overview
A deeper dive into the voter data reveals differences in county voter turnout rates. This request requires the following additional tasks:

1. Calculate the total number of votes cast in each county
2. Calculate the voter turnout for each county (%)
3. Determine which county had the highest voter turnout
## Challenge Summary
The analysis of the voting data by county shows that:
-The counties were:
  -Jefferson
  -Denver
  -Arapahoe
 -The county results were:
  -Jeferson County received 38,855 ballots
  -Denver County received 306,055 ballots
  -Arapahoe County received 24,801 ballots
 -The county with the highest voter turnout:
  -Denver
 ## Election Audit Summary
 This script enables an efficient and precise election analysis that can be configured to securely analyze all election data in the country. There are a few elements to this technology that enable is capability to meet the diverse needs of the different voting districts:
 - Efficiency: the algorithm is built for speed computing and can easily handle large amounts of data
 - Column driven database structure: any election data that is organized with CSV format can be accomodated by this tool. To give an example, the image below shows where in the code you can assign the target columns in the election data file
 #
 ![Configurable Column-Based Analysis](https://github.com/zborglin/Election_Analysis/blob/main/analysis/column_info.png)
 #
 - Complete Information Customization: There are no limits to the types of data and calculations you may implement within the script. If you want to add categorical information to describe additional data factors you may add them to the analysis. For example, you can add information regarding state election information, the congressional voting results, the funding received by each candidate, or the party affiliation. In addition, you may had any calculations to the results in order to provide the analytics that best represent the essential information. For example, you might be interested in supplementing the analysis to include the electoral votes associated with the popular vote or an analysis of the distribution of voting times relative to election day to see if voters turnout earlier in some districts. 
 
