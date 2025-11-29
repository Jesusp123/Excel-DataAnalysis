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
  - The teams were sorted by divisions
# 6. Sort the win column from most to least
  - 
