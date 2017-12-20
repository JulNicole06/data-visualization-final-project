# Summary 
The Bureau of Labor Statistics produces wage estimates annually.  This visualization compares average hourly wage estimates for 22 Major Occupational Groups from 2010 to 2016 at the state level.  By selecting an occupational group and watching the animation of wage changes throughout each year, it is obvious that certain occupational groups experienced more growth (i.e. Computer and Mathematical Occupations), compared to other occupational groups with much less growth in average wages (i.e. Farming, Fishing and Forestry Occupations).

# Design 
- Initial Visualization submitted for feedback : https://bl.ocks.org/JulNicole06/d6f7d2e5c1912778652da02eea572b23

I chose to use a map projection to easily visualize the spread of average wages across the US.  I encoded the average wages by color using a sequential scale of 9 shades of blue, since blue is a colorblind safe option, with the darker shades representing higher wages.  I used a dropdown menu to filter the data by occupational group so the reader can review each occupation individually.  I animated the data throughout each year and added buttons that the reader can use to drill down into the data further by selecting a specific year and hovering over each state to see exact wage values.  

- Final Visualiztion : https://bl.ocks.org/JulNicole06/a5f1b96e7e29f872cea4e9b292461847"

After gathering feedback, I changed the year buttons and automatic animation to a play/pause drag slider to give the reader more control over the animation as suggested in review #1.  I did not add data to show wages by county as requested in review #1 since this would take a significant amount of time to clean the data for use in this project.  This also had the added benefit of removing the h3 tag bug described in review #3 and #4.  I also used a pointer cursor to highlight clickable features and sorted the list of occupation groups as suggested in review #2.  

# Feedback 
- Review #1: "I found it interesting that perhaps the influx of movie jobs has, in part, led to an increase in wages in Georgia.  I also took away that healthcare wages have steadily increased all over the country.  Some suggestions to improve the graphic would be to have a play and pause button and to show data by county or smaller so you can see specific areas within a state that may be affected more or less by industry changes."

- Review #2: "Maybe show a pointed hand symbol to show that an item is clickable.  I like how you can go back to each year and look at more detail.  It might be helpful to put the occupations in order and give a description of what they are"

- Review #3: "The visualisation looks great. The map title seems to stay at 2016 and doesn't change to reflect the year I chose from the options."

- Review #4: "When I am choosing anything from the drop down menu in the 2nd attempt, the year changes from 2011-2016-2012-2016-2013-2016 and so on. Is that a bug?"

- Review #5: "I noticed that:

	 1) Healthcare support operations and Social service operations which are one of the noble working areas have one of the lowest wages. Even Repair and Installation sector earns more than it.  

	 2) California is one of the better places to work in as it provides one of the best average wages.  

	 3) Over the years, average wage of people employed in sectors like Computer and Management rise sharply whereas people in health sector didn't get any significant increase. 

	 4) States on the coastal regions have comparitively higher avg wage.  

	 5) Avg wages for jobs involving Computers and Management are growing at a faster rate. Hence people working in MNC's are offered more wages than the people working in unorganised sector."

# Resources 
1. https://www.bls.gov/oes/tables.htm - data in .xls format for each year downloaded from the Bureau of Labor Statistics website

2. http://colorbrewer2.org - used to select colors for choropleth scale

3. http://bl.ocks.org/StewartNoyce/9591184 - code used as template for choropleth legend

4. https://discussions.udacity.com/t/help-needed-on-tooltips/234363 - forum discussion used as template for mouseover tooltip 

5. https://bl.ocks.org/officeofjane/47d2b0bfeecfcb41d2212d06d095c763 - code used as template for play/pause drag slider 