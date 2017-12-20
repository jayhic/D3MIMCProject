Grouped Bar Chart – Issues

Is a representation of the CSV files in “Grouped Bar Chart CSV” folder divided by years to show each issue’s Number of Events, Organizations, Individuals, and Works. Then uses URL links on the bottom of the page to link to “Force Graph – Issues”
Executes by slicing the URL to acquire the last 4 characters and using if statements based on those characters. Currently it is set up to be used for the years “1973”, “1974”, and “1975”. If more years are desired to be added line 53 is the location for the if statements to open the file. Line 153 is the location of the links to the force graph for each issue.

Grouped Bar Chart – Year

Represents the Number of Events, Organizations, Individuals, and Works divided by year. With links to “Grouped Bar Chart – Issues” and “Force Graph – Year” on the bottom of the page.
As more years are added to the CSV file found at “Grouped Bar Chart CSV/Grouped Bar Chart Year Data.csv” it should update automatically with no other changes needed to the code
This file has been outdated by the Stacked Bar Chart

Force Graph – Year

Most of the work for this graph was put together by Lindsay Mattock prior to the semester beginning. I simply edited it to work for this use.
A force graph for the CSV files in “Force Graph CSV” to represent the force graph for each year. This is a force graph that connects Individuals, Organizations, and Events. Has Pan and Scroll to zoom built in. On double clicking a node it links through to the Heurist record for that node.
Executes by slicing the URL to acquire the last 4 characters and using if statements based on those characters. Currently it is set up to be used for the years “1973”, “1974”, and “1975”. If more years are desired to be added line 36 is the location for the if statements to open the file.
This file has been outdated by Date Range Force Graph

Force Graph – Issues

Most of the work for this graph was put together by Lindsay Mattock prior to the semester beginning. I simply edited it to work for this use.
A force graph for the CSV files in “Force Graph CSV” to represent the force graph for each issue. This is a force graph that connects Individuals, Organizations, and Events. Has Pan and Scroll to zoom built in. On double clicking a node it links through to the Heurist record for that node.
Executes by slicing the URL to acquire the last 5 characters and using if statements based on those characters. Currently it is set up to be used for the identifying the issues based on a “mmmyy” format. i.e. “sep73” or “jan74”. If more issues are desired to be added line 38 is the location for the if statements to open the file.
This file has been outdated by Date Range Force Graph

Date Range Force Graph

The drawing of the force graph was put together by Lindsay Mattock prior to the semester beginning. My contribution was the logic, the creating of the functions, and the addition of the date range. 
It is a force graph for the CSV at “All Force Graph - Date Range.csv”. This is a force graph that connects Individuals, Organizations, and Events based on a user input for date range using a dropdown menu. Has Pan and Zoom in it. On double clicking a node it links through to the Heurist record for that node. Nodes do not scale based on date range. Maintain a constant size of “1” regardless of number of instances. This allows a user to decide on 1 specific issue, a year, or any custom range of interest.

Stacked Bar Chart

This is a chart to show the growth of the activity of the Travel Sheet over time by showing the Number of Works, Individuals, Organizations, and Events. Shows information in “Stacked Bar Chart Year Data.csv”.

Heatmap Calendar

This is a calendar that displays the number of events on a given day. Reads file "Heatmap CSV/Heatmap Calendar - All.csv" for information. On hover it displays the date and the number of events.
This file has been outdated by Date Range Heatmap Calendar

Date Range Heatmap Calendar

This is a calendar that displays the number of events on a given day. Reads file "Heatmap CSV/Heatmap Calendar - All.csv" for information. Displays the information from a user input for date range using a dropdown menu. This allows a user to decide on 1 specific issue, a year, or any custom range of interest. On hover it displays the date and the number of events.

Donut Chart Issues

Represents the CSV files in “PieChart CSV” folder divided by years to show each issue’s Number each type of Event separated between Screening, Travel, Workshop, and Availability. Uses a tooltip developed by Justin Palmer and the CSS associated with it.

Donut Chart Years

Represents the CSV file “PieChart CSV/Years - Events.csv" which is the total Number each type of Event separated between Screening, Travel, Workshop, and Availability for the entire year. Uses a tooltip developed by Justin Palmer and the CSS associated with it.

Brakhage US Map

This is a map of the events and counts of Brakhage with circles that scale based on the number of events at a given Latitude and Longitude.
