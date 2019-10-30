# Current_SQL_Jobs_Longer_Than_Weekly_Average

Being in Operations, I wanted to set up an alert where I would receive an email if there were any SQL Server Agent jobs currently running that surpassed the jobs average weekly run time. 
This would allow me to see which jobs are taking longer than normal to execute and I can take proactive measures if required. 
This is the T-SQL command to calculate the average run time for SQL Server Agent Jobs over the past 7 days and it will return jobs that are in a processing state.
