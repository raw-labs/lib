## RAW Labs utilities

## date_range
`date_range(start_date: date, end_date: date)` <br>
Builds a collection of strings from start_date to end_date<br>
Date format is "yyyy-MM-dd"<br>

## weekday
`weekday(d: date)`  
Returns the day of the week from the date.  
0:Sunday, 1:Monday, ... 6:Saturday

## read_rss
`read_rss("http://rss.cnn.com/rss/edition_world.rss")`<br>
Returns XML structure from a RSS URL


## Statistical functions

### pearson_correlation
Return correlation value from a collection of values (x and y)<br>

`pearson_correlation( 
    [(x: 20, y: 40), 
     (x: 13, y: 26), 
     (x: 50, y: 100), 
     (x: 32, y: 64)
    ])`
    
### spearmanrank_correlation
This example shows a python integration. <br>
Returns (a collection of) two doubles: rho and p<br>

`spearmanrank_correlation( 
    [(x: 20, y: 40), 
     (x: 13, y: 26), 
     (x: 50, y: 100), 
     (x: 32, y: 64)
    ])`
