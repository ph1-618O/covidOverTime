# covidOverTime
This programs separates out each state into its own dataframe, 
cleans each new dataframe, and creates visualizations based on user imput to assit with analyzing the data.

# !> Summation & Analysis
-For this set of data the states chosen are to represent COVID cases from the supposed beginning of the outbreak to the closest date for this analysis. The figure above represents the change in cases over time for the data beginning on March 4, 2020 to August 6, 2020. Based on the graph and the data, the middle of March is when the first appreciable cases of COVID appeared. New York was the first state to recieve appreciable cases of COVID. Their cases went from a little under 10,000 to close to 300,000 cases in one month(from April to May). Other states that increase greatly in cases are Florida, Georgia, California. 

-Interesting thing to note is that the sharp rise of cases in Georgia is not predominatly included in the news. The lack of new stories and mentions of Georgia could be due to the fact that this is an election year and Florida, California and New York are all states with significant distrubutions of electoral college votes. 

-Other suggestions to consider and study is the relation of the data to the 'Shut down', when each individual state set new guidelines for the opening and closing of businesses. Further work suggested is a cumulative line for cases over the United States, and a graph that shows all the states increase over time. Limitations to consider, in the resources there isn't much information about where their sample set is coming from. To quote the website 'scrape data' is referred to however they do mention that all the data is gathered and checked by humans.


# !> Further Considerations
! Cleaning the data to just the 1st of March to the end of July

! Writing code to produce a mean shadow line for ALL STATES, and the INPUT

! Adding code to ask how many user inputs the user would like

! Exporting all the separate Globals() states into their own CSV files

! Exporting the cleaned CSV after the nans are removed for the pertinent data sets 'positive' & 'date'

! Pulling in the Mental Health Data CSV and doing all of the above with a comparison

! Incorporating the New Cases Data for all states, creating a graphical representation

! Apply Fast Fourier transform to New Cases of COVID graph

! Add linear regression stats, TBD(to be determined) on what data

! Set a line to format the string of user input if its not uniform, ie California, or Cali, or Ca, cA = CA

! Find library of full state names to compare input

# !> Credits

Code by Jen S

Cynthia, David, and Kent all assisted in setup, code development and debugging of this data aqusition.
Sarah and Latisha assisted with debugging.

# !> Resources
The data comes from the COVID Tracking Project, an organization formed by 'The Atlanic'
a newspaper and online resource for news. They collect COVID data from all 50 states and territories daily. 
COVID data from the Covid Tracking Project has been utilized by the White House, and many other popular news networks.

Link to Resource: https://covidtracking.com/
Link to CSV: https://covidtracking.com/api/v1/states/daily.csv
