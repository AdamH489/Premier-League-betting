# Premier-League-betting
I predicted the results of Premier League football matches in the 2023/24 season utilising complex statistical methods using an excel workbook. I will details the contents of the excel workbook, but I also recommend that you look through to understand the formulae and how I calculated varying parts of the workbook. 

The excel workbook has 14 sheets:

-Dashboard: Where the key information regarding expected goals of each team is, percentage chance of each team winning or a draw, percentage cover spread, fractional odds of each team winning and moneyline edge for each team and monte carlo simulation results for each team. The dashboard is structured so that the data in each area is changed if you change the home and away team. 

--monteCarlo: This sheet runs the monte carlo simulations which helps to determine the probability of each team winning, data which is then displayed in the dashboard.

- teamStats: This sheet includes data on past information for games throughout the season with home team, away team, expected goals for each team and number of goals scored for each team. Using this information, I also found the average number of goals for a home team per game and average goals conceded for the home team and the same information for the away team.

- homeStats: This shows the same data as teamStats, however teamStats shows the data in chronological order and this sheet shows it in alphabetical order for home teams. homeStats2 is the same data as homeStats.

- awayStats: This shows the same data as teamStats, however shows the data in alphabetical order for away teams. awayStats2 is the same data as awayStats.

- averageStats: This shows the average home goals for and against and the average away goals for and against for each team in the league.

- seasonalStats: This shows many stats for each team in the league.

- pDist: This shows the poisson distribution for the home and away team calculating the probability of a home win, draw and away win. It also shows the home cover and away cover.

- teamNames: This sheet shows a list of all the team names in the league.

- accuracyTest: This is a detailed sheet showing the actual data for results throughout the premier league season as well as the model home goals and away goals, the model result, what the poisson distributed predicted (i.e. home win, away win etc.). I had two columns entitled model dummy variable and pDist dummy variable where a value of 1 means that they got the result right and 0 means they didn't. I also calculated the model accuracy and the poisson distribution accuracy; and at the end of the season I found that the poisson distribution was more accurate than the model.

- bettingOpportunities: This is another detailed sheet which shows the data for results in the premier league season as well as the odds for the home team and away team of winning the game, the money line edge for the home and away teams. I then made a few columns which stated that if the moneyline edge is greater than 10%, place a bet of £10 and if it wins, you win the money listed from the odds and if not, then you lose the £10, but the model says whether to place the bet. I then created some more columns doing the same thing for 20% and 30% moneyline edges. Afterwards, I calcualted the total profit and loss for home team, away teams and overall for the varying levels of moneyline edge and all lost but to varying amounts.

- odds: This sheet details all the odds and moneyline edges for home and away teams throughout the season.

A few advantages of this workbook is that you can access the information for various teams easily through the dashboard and also as the data has live connections, the data is added as the season progresses meaning that yo don't have to manually type in the data when a new weeks of games are played. 
