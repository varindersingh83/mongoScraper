![](datascraper.gif)



Webscaper build in JS to scarape data and store it in mongodb and express backend.

`Show news` shows data already in mongoDB

`Scrape & Show` does following
 - clears the data in mongodb
 - srapes data from hackernews
 - inserts data in mongodb
 - show data in frontend

using 2 experss API

endpoint : /scrape
method: get 
 - clears the data in mongodb
 - srapes data from hackernews
 - inserts data in mongodb

endpoint : /all
method: get 
- get data already in mongoDB


Datatbase - MongoDB
collection : scrapedData
field name : title, link, time and id