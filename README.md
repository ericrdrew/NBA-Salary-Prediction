# NBA-Salary-Prediction

NBA Salary Prediction(NBASalaryProject.Rmd):

Read in Salary, Total Stats, Advanced stats, and Per 100 stats from Bball-Ref from the 2021 season, with the goal of predicting a player's 2022 salary based on their 2021 statistics. Removed redundant variables and merged all 4 files onto each other into master dataset.

Checked for multi-collinearity using correlation matrices and removed problem variables.

Proceeded to run a multitude of step-wise regression tests including/removing a handful of variables that seemed to be throwing diagnostic tests for a loop. Eventually moved forward with the model that had cleanest diagnostics and lowest AIC/BIC values compariatively. Handful of diagnostic tests failed.

Final test on the latest year of salary data yielded a MAE of a little over $3M.

Data used: perGameStats.csv, Salary.csv, advancedStats.csv, per100.csv, totalStats.csv

Sources:

https://www.basketball-reference.com/contracts/players.html

https://www.basketball-reference.com/leagues/NBA_2022_totals.html

https://www.basketball-reference.com/leagues/NBA_2022_advanced.html

https://www.basketball-reference.com/leagues/NBA_2022_adj_shooting.html

NBA Clustering(NBAClustering.Rmd)