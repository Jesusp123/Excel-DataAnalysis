# Excel-DataAnalysis
# PURPOSE
To demonstrate how Excel can be used for Data Analysis

## Actions
# 1. Clean Datasheets
  - space out columns to make them more legible
  - Delete any unnecessary columns
# 2. Change old NFL Teams to their current name
  - CTRL+H = Find and Replace Box
# 3. Find all Unique Football Teams
  - =UNIQUE(NFL!B2:B673)
# 4. Find the total wins of all teams during the specified time period
  - =SUMIF(NFL!$B$2:$B$673,A2,NFL!$C$2:$C$673)
# 5. Sort teams by most wins
  - =SORTBY(A2:A33,B2:B33,-1)
  - Divisions sorted the teams
# 6. Sort the win column from most to least
  - =SORT(B2:B34,1,-1)
# 7. Find the most wins in a season for each franchise
  - =MAXIFS(NFL!$C$2:$C$673,NFL!$B$2:$B$673,C2)
# 8. Find the Most Losses in a season for each franchise
  - =MAXIFS(NFL!$D$2:$D$673,NFL!$B$2:$B$673,C2)
# 9. Make a chart depicting the win totals of different franchises
  - Collect Data from the 8 best and the 8 worst teams
  - Make a column chart
# 10. Make a chart depicting the max wins and max losses in a singles season of different franchises
  - Collect Data from the 8 best and the 8 worst teams
  - Make a column chart
# 11 Find average offensive yards per season
  - =AVERAGEIF(NFL!$B$2:$B$673,A2,NFL!$J$2:$J$673)
# 12 Find average Offensive Touchdowns per season
  - =AVERAGEIF(NFL!$B$2:$B$673,A2,NFL!$S$2:$S$673)
# 13. Find the average Rushing Touchdown per season
  - =AVERAGEIF(NFL!$B$2:$B$673,A2,NFL!$Y$2:$Y$673)
# 14. Make a chart comparing the average Passing and rushing touchdowns
  - Collect Data from the 8 best and the 8 worst teams
  - Make a column chart
# 15. Countif seasons with 5000 yards and 30 Touchdowns
  - =COUNTIFS(NFL!$B$2:$B$673,A2,NFL!$R$2:$R$673,">4000",NFL!$S$2:$S$673,">30")
# 16. Make a chart to show how many seasons with 5000 yards and 30 passing Touchdowns each top teams have had
  - Collect data from the 11 teams with the most wins
  - Make a pie Chart
  - If the team is not shown, then their total is 0
# 17. Calculate QB quality, throughout the charted timeframe, based on average Passing TDS
`- =IFERROR(IFS(H2>25,"Great QB",H2<22,"Bad QB"),"OK QB")





# 20 pivot table
