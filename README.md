# The effect of Gerrymandering on the political ideology (Polarisation) of the House of Representatives Members
---
## Summary Overview

This paper explores the increasing polarization in the political ideology among members of the U.S. House of Representatives (HOR), focusing on the role of gerrymandering - the strategic redrawing of district lines. It argues that gerrymandering is a catalyst for political polarization in the HOR, facilitating factors such as voting preferences, demographic changes, and media influence. The paper highlights the shift from a moderate political ideology to more extreme positions, incentivized by the undemocratic nature of gerrymandering, which encourages incumbents to align with their most vocal voters. Through a quantitative analysis of nominal data, the paper seeks to provide empirical evidence supporting the claim that gerrymandering contributes significantly to the political polarization observed in the HOR. The study also reviews existing literature to build a case for the impact of gerrymandering on the political landscape and proposes hypotheses regarding the causal relationship between gerrymandering and political polarization.

## Data

- DW-Nominate Score Data: [here](https://voteview.com/data)

- Raw Election Results: [here](https://history.house.gov/Institution/Election-Statistics/)

## Methods
### Data Set 1: Realtime Nominate Ideology and Related Data
- **Purpose**: To quantify the political ideology of House of Representatives (HOR) members.
- **Method**: Utilizes the DW-NOMINATE score method, a mathematical approach developed by Professor Jeffrey M. Lewis at UCLA.
- **Key Variable**: DW-NOMINATE score, where a score of 0.3 or above indicates polarized ideology.
- **Time Frame**: 2010 to 2020 (111th to 116th Congress).

### Data Set 2: Election Statistics
- **Purpose**: To provide raw election data showing the results of HOR elections.
- **Data**: Includes every House of Representatives election result by year, state, and district from 2010-2020.
- **Key Variable**: Voting count for each district in each state, categorized by Democrat or Republican votes.
- **Source**: Government-counted ballots.

### Analysis Approach
- **Data Merging**: Merges the two datasets by state, district, and year to create a combined dataset with a unique key for each data point.
- **Correlation Study**: Aims to observe voting pattern shifts between 2010-2020 and identify correlations between gerrymandering and political polarization in the HOR.
- **Efficiency Gap Calculation**: Uses a mathematical equation to determine if a state has been gerrymandered, with an efficiency gap of over 7% indicating a gerrymandered state.

## Authors

Camilla de Pourbaix (camilladepourbaix@college.harvard.edu): 
- Ownership of project study & for the writing at hand

Simon Lee (simonlee711@g.ucla.edu): 
- Responsible for data collection/clean-up, producing figures, & running analysis 
