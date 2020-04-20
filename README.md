# Tableau-projects
Various Tableau projects

Project descriptions:
Coronavirus (COVID-19) Cases.twbx
* Dashboard showing the spread of COVID-19 within the United States, showing both confirmed cases and deaths, per date, from January to April. Includes a bar chart and two maps (one for confirmed cases and one for deaths), as well as a synchronized sliding date selector.
* Room to grow: The axis range is fixed at the maximum for the entire period, and earlier on (ie. January) the first few cases are not visible since they're so small compared to the axis range. I couldn't find a good way to get per-pane axis maximums. This problem extends to the sorting of the states in the chart; the first state for every pane in Descending is always New York in every date (even when, for example, Washington has 1 case) because New York has the most cases for the entire period. I tried changing measures and implementing reference lines to change the axis range, but it has not worked yet.

TarkovArmoredItems.twbx
* Dashboard showing all the armored items in video game Escape from Tarkov, allowing easy comparison of detriments and armor classes. Includes filter selectors for type and armor class.
* Room to grow: There are a lot of different measures for the different items that are not implemented in this graph that I would eventually want added (namely, a more accurate way to show weight than a size mark). Also, a way to export it in a non-TWBX file (but so it's still dynamic!) so that people without Tableau could use it would be nice, but it seems to be a limitation of Tableau.
