# Mobile-App-Assignments
The purpose of this assignment is to give us a better understanding of your learning skill. If you have any questions or need any clarifications for this challenge, please get in touch!
## Goal 1:

#### Develop a Currency Conversion App that allows a user view exchange rates for any given currency

- [ ] Create a Project for a Mobile Phone
- [ ] Android: _Kotlin_ | iOS: _Swift_  You can learn Kotlin/Swift easily I'm sure:))

### Functional Requirements:
- [ ] Exchange rates must be fetched from: https://currencylayer.com/documentation  
- [ ] Use free API Access Key for using the API
- [ ] User must be able to select a currency from a list of currencies provided by the API(for currencies that are not available, convert them on the app side. When converting, floating-point error is accpetable)
- [ ] User must be able to enter desired amount for selected currency
- [ ] User should then see a list of exchange rates for the selected currency
- [ ] Rates should be persisted locally and refreshed no more frequently than every 30 minutes (to limit bandwidth usage)
- [ ] Write unit testing

### UI Suggestion:
- [ ] Some way to select a currency
- [ ] Some text entry widget to enter the amount
- [ ] A list/grid of exchange rates
- [ ] It doesn’t need to be super pretty, but it shouldn’t be broken as well ;)

### What we're looking for:
- [ ] An App that meets the Functional Requirements above
- [ ] Your coding style! Show us how you like to write your code
- [ ] Architecture, how you've structured your code
- [ ] Principles, how you belive code should be written
- [ ] Qualities, how you guarantee your code is functioning

## Goal 2:

#### Develop a sample app that fetches alist of recent paying movies from the Movie Database(tmdb).

- [ ] Create a Project for a Mobile Phone
- [ ] Android: _Kotlin_ | iOS: _Swift_  You can learn Kotlin/Swift easily I'm sure:))

### Functional Requirements:
- [ ] Connect to tmdb and retrieve a list of movies that are “Now  Playing”. 
- [ ] Use this endpoint to retrieve the movies: https://api.themoviedb.org/3/movie/now_playing  
- [ ] Doc: https://developers.themoviedb.org/3/movies/get-now-playing 
- [ ] Website: https://www.themoviedb.org/ 
- [ ] Use free API Access Key for using the API . API key: 34c902e6393dc8d970be5340928602a7 
- [ ] Displaying movies in a layout you like. For each movie in your layout, please include the movie title, and a poster image.
- [ ] Users need to be able to favourite a movie locally, and view them whenever they like. (Save to local disk for offline support) 
- [ ] Implement a local storage to persist results and favourited movies to disk. 
- [ ] Optional:  Anything you like to expand the functionality of the app. 
- [ ] Write unit testing

## Goal 3:

#### The exercise involves build a “proof of concept” app which consumes a REST service and displays photos with headings and descriptions. The exercise will be evaluated on coding style, understanding of programming concepts, choice of techniques, and also by the developer’s process, as indicated by the trail of git commits.

- [ ] Create a Project for a Mobile Phone
- [ ] Android: _Kotlin_ | iOS: _Swift_  You can learn Kotlin/Swift easily I'm sure:))

### Functional Requirements:
- [ ] Ingests a json feed https://dl.dropboxusercontent.com/s/2iodh4vg0eortkl/facts.json
- [ ] You can use a third party Json parser to parse this if desired.
- [ ] Displays the content (including image, title and description) in a table
- [ ] The title in the navbar should be updated from the json
- [ ] Each row should be the right height to display its own content and no taller. No content should be clipped. This means some rows will be larger than others.
- [ ] Don’t download all images at once, only as needed
- [ ] Refresh function, either a refresh button or use pull down to refresh.
- [ ] Should not block UI when loading the data from the json feed.

## Goal 4:
#### Develop a sample app that display Corona Virus statistics and Advice.

- [ ] Create a Project for a Mobile Phone
- [ ] Android: _Kotlin_ | iOS: _Swift_  You can learn Kotlin/Swift easily I'm sure:))

### Functional Requirements:
- [ ] Corona Virus Stats & Advices App
- [ ] Base URLhttps://services1.arcgis.com/0MSEUqKaxRlEPj5g/ArcGIS/rest/services/ncov_cases/FeatureServer?f=pjson
- [ ] Current statistics of global total confirmed, deaths, recovered cases.
- [ ] Statistics of countries and regions total cases count
- [ ] World map with annotation pin and description of affected regions
- [ ] Datasets is provided by ArcGIS Esri Corona Virus dataset.
- [ ] Basic advice to prevent and handle virus, myth busters Q&A from WHO.


### When you're done...

Zip your completed Project and email the .zip file.
If you want to instead make a github repo and just send us a link to it, that's fine too but please do __not__ fork this repo thanks!

Have fun!
