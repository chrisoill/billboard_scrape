# billboard_scrape
Code I used to scrape the weekly songs on the billboard hot 100 chart.

Creates a file with the song titles, artist names, current ranking, last week's ranking, top position, and number of weeks on the chart.

If you plan to use this multiple times over a span of multiple weeks, I would suggest adding a column that also includes the current date whenever running the script, adding the code: 

```
top_100['date'] = date.date.today()
```
