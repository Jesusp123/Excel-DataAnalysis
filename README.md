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
# 11. Countif seasons with 5000 yards and 15 ints
# 12. Year of the most wins
# 13 year of the most losses
# 14 average if offensive yards
# 15 average if defensive tds
# 16 if statement- tds-Good ok or bad QB
# 17 teams that end with rs
# 18 chart
# 19 chart
# 20 pivot table
