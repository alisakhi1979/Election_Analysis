# Election_Analysis
## **Overview of Election Audit**

**Purpose:** 
    The Election Commision in the state of Clorado has requested audit of the recent congressional election. This audit includes the analysis of the balots casted in three counties i.e. Jefferson, Denver and Arapahoe. 

**Objectives:** 
    The overarching objectives and related deliverables for this analysis are the followings:

    - Analyse the raw data of the balots inorder to generate the below outputs:
        1. Calculate the total number of votes
        2. Complete list of andidates who received votes
        3. Total number of votes each candidate received
        4. Percentage of each candidate won
        5. Winner of the election based on popular votes
        6. Voter turnout for each county
        7. Percentage of votes from each county out of the total count
        8. County with the highest turnout

    - Automate the analysis with Python script that generates following deliverables:
        1. Election Results Printed to the Command Line
        2. Election Results Saved to a Text File

**Resources:**
1. Data Source: election_results.csv
2. Software: Python 3.6.1, Visual Studio Code 1.38.1

**Elecction-Audit Results:**
    
    1. There were *369,711* vote cast in the election
    2. The breakdowns of the number of votes and percentage of the votes for three counties were:
        - Arapahoe: 24,801 (6.7%)
        - Denvor: 306,055 (82.8 %)
        - Jefferson: 38,855 (10.5 %)
    3. County with the largest voter turnout was: 
        - *Denvor*: 82.8 % of the vote and 306,055 number of vote were casted in this county.
    4. The candidates results were:
        - *Charles Casper Stockham* received 23.0% of the vote and 85,213 number of votes.
        - *Diana DeGette* received 73.8% of the vote and 272,892 number of votes.
        - *Raymon Anthony Doane* received 3.1% of the vote and 11,606 number of votes.
    5. The winner of the election was:
        - *Diana DeGette* who received 73.8% of the vote and 272,892 number of votes.
        
**Election-Audit Summary:**

    This election audit was successfuly completed and deliverables as instructed by the election commission were delivered. The Python script developed for this audit can be replicated for analysis of other counties election within the state. In addition, the script can be further enhanced to analyse the election at the district level and party level. 

    For the district level analysis a dictionary can be created to contain all 8 districts as the key and a list of related counties e.g. district = {District_1:[ X county, Y county, ...], Distrrict_2:[ A county, B county,...], ... , District_8: [ Z county, ...]}. Once, the dictionary is completed the District count of votes can be tracked in the same way that vote count for counties are tracked in the Python script.

    For the party level analysis a dictionary can be created to contain the name of prties as the key and their affiliated candidates as the list of values i.e. party_affiliation = {Republican: [ Candidate A, Candidate B, ...], Democrat: [Candidate M, Candidadte N, ...], Independent: [Candidate Y, Candidate Z]}. Once this affiliation is recorded in the dictionary, the script can keep track of the vote counts for the parties and identify the wining parties at the county level, district level and state level.
 
        
