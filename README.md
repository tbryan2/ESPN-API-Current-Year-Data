# ESPN-API-Current-Year-Data
[Video Tutorial](https://youtu.be/S_ax0rjAoXE)

## Objective
Getting Current Fantasy Football League Data w/ Python &amp; ESPN API

## Details

### Setup
The four libraries we need for this project are: pandas, numpy, and matplotlib. Use pip to install all of these on your machine.

We also need to find some Cookies values to access ESPN private fantasy football league data. The values we need are leagueId, swid, and espn_s2. To get leagueId simply log into your ESPN league and look at the end of the url for where it says _?leagueId=123456_. Paste this number value in the corresponding variable in you config.py file. 

To find our cookies values, swid and espn_s2, log into your ESPN league in a browser and anywhere on the page right-click and hit Inspect Element. In the Storage tab of your browser developer tools, scroll down to espn.com and find swid and espn_s2. Copy and paste these values in your config.py file.

## Results
![Screen Shot 2022-09-15 at 1 04 07 PM](https://user-images.githubusercontent.com/29851231/190506442-8a1dc5eb-41dd-4ad4-be61-e8e889bb4e4e.png)

### Sources/Helpful Resources:

- https://stmorse.github.io/journal/espn-fantasy-2-python.html
- https://stmorse.github.io/journal/espn-fantasy-3-python.html
- https://stmorse.github.io/journal/espn-fantasy-v3.html
- https://andrew-picart.medium.com/data-cleaning-and-eda-with-espn-fantasy-football-1b13346ebdca
