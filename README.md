
# Name
liri-node-app

# Link
Deployment Link https://arielqns.github.io/liri-node-app/
GitHub Resipository Link: https://github.com/jahdasha/liri-node-app
Link to video: https://drive.google.com/file/d/13UJ7KfphId25lVUqwa15ah2jnVtxNwNj/view

# Created by
Ariel Quinones September 2019

# Description
This web application is called LIRI, a language interpretation and recognition interface. LIRI takes in commands' parameters and returns back data. In this app it will take four different comands and search in Spotify for songs, Bands in Town for concerts, and OMDB for movies. Requests will be send using the axios package to the Spotify, Bands in Town and OMDB APIs.


# Instructions:
- Open liri-node-app file in your terminal

- Provide one of the four commands with a parameter:
a. node liri.js concert-this <artist/band name here>'
b. node liri.js spotify-this-song '<song name here>'
c. node liri.js movie-this '<movie name here>'
d. node liri.js do-what-it-says 

- Execute to see a list of results
 a. for concerts you will see:
 Name of Venue
 Venue Location 
 Dates

 b. for songs you will see:
 Artist(s)
 Song Name
 Preview link of the song from Spotify
 The album that the song is from

 c. for movies you will see:
 Title
 Released year
 IMDB rating
 Rotten Tomatoes Rating
 Country where it was produced
 Language
 Plot
 Actors

 d. for command do-what-it-says, it will pick text from random.txt and return back information about songs with that title. 


- Information will be log in the log.txt file




# Created using: 
Javascript, Node.js, NPM packages: Axios, Node-Spotify-API, Request, Moment, DotEnv. Bands in Town and OMDB APIs. 