
# Statistical data analysis

This repository contains a project focused on distribution analyzing that representing sales results using statistical methods and visualization techniques and conducting A/B testing.

## Technologies:
Python (pandas, numpy, scipy, statmodels, matplotlib, seaborn)

## Statistics Analysis
- **Testing Sample for Normality**:
   This part of the project involves testing the sample data for normality using visualization methods and statistical tests.
- **Analysis of Sales Results**:
   The sales results are analyzed using Z-Test and two-sample Z-Test to determine the significance of differences.

## A/B Test Analysis
The project focuses on analyzing the results of an A/B test where the first gate in Cookie Cats was moved from level 30 to level 40. 

### Specifically, it examines the impact on player retention.

This is a classic puzzle game where players must match tiles of the same color to clear the board and win levels. The game features singing cats on the board.
During gameplay, players encounter gates that force them to wait for some time before they can progress or make in-app purchases. 

### Another aspect of A/B testing involves investigating the dependency between conversion rate values and two different game versions.

Variables in the dataset include:
- userid: _A unique identifier for each player._  
- version: _Whether the player was assigned to the control group (gate_30 - gate at level 30) or the test group (gate_40 - gate at level 40)._  
- sum_gamerounds: _The number of game rounds played by the player during the first week after installation._  
- retention_1: _Whether the player returned and started playing 1 day after installation._  
- retention_7: _Whether the player returned and started playing 7 days after installation._  

Players were randomly assigned to either the gate_30 or gate_40 group when installing the game.  
