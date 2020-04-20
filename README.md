# Tableau-projects
Various Tableau projects

Project descriptions:
Coronavirus (COVID-19) Cases.twbx
* Dashboard showing the spread of COVID-19 within the United States, showing both confirmed cases and deaths, per date, from January to April. Includes a bar chart and two maps (one for confirmed cases and one for deaths), as well as a synchronized sliding date selector.
* Room to grow: The axis range is fixed at the maximum for the entire period, and earlier on (ie. January) the first few cases are not visible since they're so small compared to the axis range. I couldn't find a good way to get per-pane axis maximums. This problem extends to the sorting of the states in the chart; the first state for every pane in Descending is always New York in every date (even when, for example, Washington has 1 case) because New York has the most cases for the entire period. I tried changing measures and implementing reference lines to change the axis range, but it has not worked yet.
