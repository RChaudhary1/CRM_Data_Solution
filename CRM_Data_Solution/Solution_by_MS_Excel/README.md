# Process involved in solving the problem and observations

## Steps:
Extracted Day, Month, Month Name and Year from the Date of Contact column.
Created a Pivot table on using the dataset to calculate the Count of Clinets Contacted in a month.
Created another pivot table to calculate count of unique clients contacted in a month. (Changed value field settings in the pivot table settings to change the 'Summarized value field by' from 'count' to 'distinct count')
Created following graphs in the dashboard sheet of the workbook:
1) Total_client_distribution_count - Bar graph of total count of the clients contacted during a month. Year can be changed using the dropdown at the top left corner.
2) Total_client_distribution_percentage - Percentage ditribution of the total clients contacted during a month. Year can be changed using the dropdown at the top left corner.
3) Total_unique_client_distribution_count - It is possible that same client was contacted more than one time in a month. This graph is bar graph of total count of distinct clients contacted during a month. 
4) Total_unique_client_distribution_percentage - Percentage distribution of distinct/unique clients contacted during a month



## Result:

Maximum contacts in a month (October) - 213 (21%)
Maximum distinct clients contacted in a month (October) - 35 

Total contacts made by the team was 213 during the month of October which is 21% of the total contact made by the team. 
Since, it is possible that the same client was contacted more than once in the same month, we also calculated the distinct number of clients contacted in each month and again October is the month when the team tend to contact the greatest percentage of its clients.
