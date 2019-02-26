# LIRI-node-app

**LIRI BOT**

**LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.**

**LIRI will search Spotify for songs, Bands in Town for concerts, and OMDB for movies.**

**What Each Command Does**


**node liri.js concert-this <artist/band name here>**

This will search the Bands in Town Artist Events API ("https://rest.bandsintown.com/artists/" + artist + "/events?app_id=codingbootcamp") for an artist and render the following information about each event to the terminal:

Name of the venue

Venue location

Date of the Event (use moment to format this as "MM/DD/YYYY")

![My image](danbrit.github.com/LIRI-node-app/img/concert-this.jpg)



**node liri.js spotify-this-song '<song name here>'**

This will show the following information about the song in your terminal/bash window

Artist(s)

The song's name

A preview link of the song from Spotify

The album that the song is from

![My image](danbrit.github.com/LIRI-node-app/img/spotify-this.jpg)


**node liri.js movie-this '<movie name here>'**

This will output the following information to your terminal/bash window:

* Title of the movie.
* Year the movie came out.
* IMDB Rating of the movie.
* Rotten Tomatoes Rating of the movie.
* Country where the movie was produced.
* Language of the movie.
* Plot of the movie.
* Actors in the movie.

![My image](danbrit.github.com/LIRI-node-app/img/movie-this.jpg)


**node liri.js do-what-it-says**

Using the fs Node package, LIRI will take the text inside of random.txt and then use it to call one of LIRI's commands.    

![My image](danbrit.github.com/LIRI-node-app/img/do-what.jpg)
