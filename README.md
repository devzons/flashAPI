## WEB API

* Facebook API
* GooglePlaces API
* Reddit API
* Twitter API
* Weather API
* Yelp API


## Search for Podcasts about "code"
https://itunes.apple.com/search?tern=code&entity=podcast

## Search for Harry Potter Movies
https://itunes.apple.com/search?term=harray-potter&entity=movie

## Request thru javascript code
```
var request = require('request');
request('http://www.reddit.com', function(error, response, body) {
  if(error){
    console.log("ERROR!!!");
    console.log(error);
  } else {
    if(response.statusCode == 200){
      console.log(body);
    }
  }
});
```
## Sunset time 

https://developer.yahoo.com/weather/

## Movie API

General search: 
http://www.omdbapi.com/?s=guardians+of+the+galaxy&apikey=thewdb
Search with Movie ID: 
http://www.omdbapi.com/?i=tt3896198&apikey=thewdb

you must append &apikey=thewdb to the end of your url

