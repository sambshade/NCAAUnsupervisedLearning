# Unsupervised Machine Learning Project - Clustering NCAA Men's Basketball Statistics from 2010 - 2023 for Ranking Potential 2024 Winners.
## University of Colorado - Boulder M.S.D.S: DTSA 5510 Unsupervised Algorithms in Machine Learning
## Project Description:

As March 2024 is on the horizon, millions of Americans will be filling out their brackets to predict who will be the winner of the 2024 NCAA Men's Basketball Championship. The following project uses clustering methods (K-Means Clustering and Hierarchical Clustering) as well as PCA to place 2024 teams into tiersets based on their performance so far this season. The datasets chosen can be found from the KenPom https://kenpom.com/ statistics page. This page examines advanced statistics for NCAA Men's Basketball teams, players, and coaches. From this page, four dataset categories were chosen and described below:

- **FG2Pct:** 2-Point Field Goal Percentage         
- **RankFG2Pct:** Rank - 2-Point Field Goal Percentage
- **FG3Pct:** 3-Point Field Goal Percentage        
- **RankFG3Pct:** Rank 3-Point Field Goal Percentage      
- **FTPct:** Free Throw Percentage              
- **RankFTPct:** Rank Free Throw Percentage
- **BlockPct:** Block Percentage          
- **RankBlockPct:** Rank Block Percentage    
- **OppFG2Pct:** Opponent 2-Point Field Goal Percentage        
- **RankOppFG2Pct:** Rank Opponent 2-Point Field Goal Percentage
- **OppFG3Pct:** Opponent 3-Point Field Goal Percentage       
- **RankOppFG3Pct:** Rank Opponent 2-Point Field Goal Percentage
- **OppFTPct:** Opponent Free Throw Percentage        
- **RankOppFTPct:** Rank Opponent Free Throw Percentage     
- **OppBlockPct:** Opponent Block Percentage    
- **RankOppBlockPct:** Rank Opponent Block Percentage
- **FG3Rate:** 3-Point Field Goal Rate      
- **RankFG3Rate:** Rank 3-Point Field Goal Rate
- **OppFG3Rate:** Opponent 3-Point Field Goal Rate
- **RankOppFG3Rate:** Rank Opponent 3-Point Field Goal Rate
- **ARate:** Assist Rate       
- **RankARate:** Rank Assist Rate       
- **OppARate:** Opponent Assist Rate       
- **RankOppARate:** Rank Opponent Assist Rate
- **StlRate:** Steal Rate        
- **RankStlRate:** Rank Steal Rate
- **OppStlRate:** Opponent Steal Rate
- **RankOppStlRate:** Rank Opponent Steal Rate
- **DFP:** Defensive Footprint
- **NSTRate:** Non-Steal Turnover Rate
- **RankNSTRate:** Rank Non-Steal Turnover Rate
- **OppNSTRate:** Opponent Non-Steal Turnover Rate   
- **RankOppNSTRate:** Rank Opponent Non-Steal Turnover Rate 

Summary Statistics:
- **Tempo:** Tempo; pace of game
- **RankTempo:** Rank Tempo; pace of game
- **AdjTempo:** Adjusted Tempo (for strength of schedule)	
- **RankAdjTempo:** Rank Adjusted Tempo (for strength of schedule) 	
- **OE:** Offensive Efficiency 
- **RankOE:** Rank Offensive Efficiency
- **AdjOE:** Adjusted Offensive Efficiency (for strength of schedule) 
- **RankAdjOE:** Rank Adjusted Offensive Efficiency (for strength of schedule)
- **DE:** Defensive Efficiency
- **RankDE:** Rank Defensive Efficiency
- **AdjDE:** Adjusted Defensive Efficiency (for strength of schedule)	
- **RankAdjDE:** Rank Adjusted Defensive Efficiency (for strength of schedule)
- **AdjEM:** Adjusted Efficency Margin (for strength of schedule)
- **RankAdjEM:** Rank Adjusted Efficency Margin (for strength of schedule)

Offensive Metrics:
- **eFGPct:** Effective Field Goal Percentage
- **RankeFGPct:** Rank Effective Field Goal Percentage 
- **TOPct:** Turnover Percentage
- **RankTOPct:** Rank Turnover Percentage	
- **ORPct:** Offensive Rebounding Percentage	
- **RankORPct:** Rank Offensive Rebounding Percentage	
- **FTRate:** Free Throw Rate
- **RankFTRate:** Rank Free Throw Rate

Defensive Metrics:
- **eFGPc:** Opponent Effective Field Goal Percentage
- **RankeFGPct:** Rank Opponent Effective Field Goal Percentage
- **TOPct:** Opponent Turnover Percentage
- **RankTOPct:** Rank Opponent Turnover Percentage
- **ORPct:** Opponent Offensive Rebounding Percentage
- **RankORPct:** Rank Opponent Offensive Rebounding Percentage
- **FTRate:** Opponent Free Throw Rate
- **RankFTRate:** Rank Opponent Free Throw Rate
The process include combining datasets from different years, cleaning the data of the individual categories above, performing exploratory data analysis (EDA) to indicate Top 10 teams for every variable, performing the clustering method, and finally placing 2024 teams in tiers based on clusters.

# Conclusion:
Overall the tier ratings did not adequately portray the Top 15 teams per the Vegas Odds. The K-Means Clustering Method indicated that Western Kentucky was the only Tier 1 team, who is most likely not probable to win the tournament or even participate. Additionally, the top 15 teams of the Vegas odds were ranked Tier 3 or below. The Hierarchical Clustering Method did show some sign of improvement but by a very modest amount. The only team from the top 15 ranked in Tier 2 was Alabama. Additionally, there were some teams present in this tier that most likely would not make the tournament. Additional future work for this project would be to increase the number of clusters (as only 5 were utilized) to separate the teams a bit more. The winner's cluster numbers were all very close, as the most common cluster was typically close followed by the second most common cluster for several categories. 

Disclaimer: all data and property belongs to KenPom Statistics. The following project doesn't not aim to provide insights for gambling or aim to make a profit off of the analysis. This project was strictly for educational purposes.
