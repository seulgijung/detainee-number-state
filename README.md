# Auto-updating number of detainees website

## What I wanted to accomplish
The table on the website is... horrifying. It updates numbers periodically by addinf a new row on the top, resulting in 16,682 rows stacked (ascending=False!!), as of Dec 8, 2025, without any filter. I'd like to visualize it effectively to show how many people are held up by each state.

## Summary of the data sources and the collection process (with links) 
Data source: TRAC Immigration
The Transactional Records Access Clearinghouse (TRAC) is a data gathering, data research, and data distribution organization that was founded in 1989 at Syracuse University.
https://tracreports.org/immigration/detentionstats/facilities.html
Unfortunately, the GPT temporary chat had vanished the moment I started a new regular chat.... 

## New skills, approaches, etc you used, or where you grew the most during the project
I tried to scrape the table but ended up using the LLM for playwright. I think I improved a bit in Datawrapper, knowing how to produce a toolkit and stuff. 

## Things you tried to do or wanted to do but did not have the skills/time (but if you have more time you might do)
I could've added another column in which abbreviated state names were turned into full ones, helping readers who are not familiar with abbreviations understand the map. But I managed to change the font style, size and have the graphic and short notes horizontally placed.
