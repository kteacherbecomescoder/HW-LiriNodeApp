# LIRI-node-app

Language, Interpretation and Recogonition Interface

LIRI will search Spotify for songs, Bands in Town for concerts and OMDB for movies.

## Installing

Once you've cloned the repository, you'll need to install the required node packages listed in packages.json. They are: node-spotify-api, request, moment and dotenv. This is done with a simple npm install command.

After the packages are installed you'll be able to run 'node liri.js'

## Interacting with LIRI

You may either enter in one of the commands as an argument; "concert-this", "spotify-this-song", "movie-this", or "do-what-it-says", or alternatively enter in no arguments for a interactive menu.

For "concert-this", "spotify-this-song", or "movie-this" you'll also need to enter in an artist/band, song title, or movie title to search for.

concert-this will run a search on bandsintown.com and list all the upcoming concerts, with their name, venue location, and the date's listed for the given artist/band.


spotify-this-song will search Spotify for all songs with the given title and list their artist(s), song name, album, and a link to the song preview.

movie-this will search the OMDB and give you information on the movie including it's release year, IMDB rating, country of production, language, a short plot, and the starring actors.

do-what-it-says will read a random.txt file, and run the command stored in the text file.

Here are some command images for each search:
/images/Search For Concert by Artist.png
/images/Search - Do What It Says!.png
/images/Search for Movie.png
/images/Search for Song on Spotify.png

