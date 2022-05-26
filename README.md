# Election Analysis
## Overview of Election Audit: 
### Purpose
 * Create scripts that read, write, and store data from files or in arrays.
 * Perform mathematical operations.
 * Use decision statements, logical operations for complex comparisons, and repetition statements to run code more than once.
 * Produce screen outputs.
## Election-Audit Results:
-	There were **369,711** votes cast in the election
-	The counties in the precinct were-
	-	Jefferson
	-	Denver
	-	Arapahoe
-	The county results were-
	-	Jefferson received **10.5%** of the votes and **38,855** number of votes
	-	Denver received **82.8%** of the votes and **306,055** number of votes
	-	Arapahoe received **6.7%** of the votes **24,801** number of votes
-	The County  with largest turnout: **Denver**
-	The candidates were-
	-	Charles Casper Stockham
	-	Diana DeGette
	-	Raymon Anthony Doane
-	The candidate results as were-
	-	Charles Casper Stockham received **23.0%** of the votes and **85,213** number of votes
	-	Diana DeGette received **73.8%** of the votes and **272,892** number of votes
	-	Raymon Anthony Doane received **3.1%** of the votes **11,606** number of votes
-	The winner of the election was **Diana DeGette** who received  **73.8%** of the votes and **272,892** number of votes
-	Command line Output:
-
-	## Election-Audit Summary: 

#### Business proposal for Election Commission

- **Introduce Federal, state, local and tribal election categories**
	- New functionality to count votes at state level by including additional source data columns like state,office, district,party, year of elections as required. This will provide the analysis for elections at  various levels.
	- ***Example 1**: Add new dictionary to hold data for different states and its votes. One can calculate state vote percent and total state votes.
	- ***Example 2**: Add new dictionary to hold data for different years. One can calculate yearly vote percent and total yearly votes.
- **Graphs**
	- Using `Matplotlib` library in python the script can be used to generate year-wise, state-wise, district-wise graphs. The graphs can be drawn for any dimensions and metrics like vote counts and vote percentage.
- **Categorize Election results**
	- Using conditional analysis the script can help determine if elections were successful or not using specific success criteria.
- **Support multiple Data sources**
	- The script can be modified to use various data source types like database, real-time feeds, JSON files etc.
