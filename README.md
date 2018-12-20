
# OracleX

A web app that lets you sort your music .
Explore your playlists to understand how and why it affects your state. Change attributes such as the tempo, energy and danceability.
Sort it the way you want. Either linearly or by playing with the curve. To get puped up, slow down a bit first, then again sort by increasing energy!


Online at

[https://oraclex.zonenow.io/](https://oraclex.zonenow.io/)


## Local Development

The following section describes how to develop OracleX locally. It requires a Spotify API key.

Install leveldb

    $ brew install leveldb

Install requirements for API server:

    $ pip install -r server/requirements.txt


Edit web/config.js to update SPOTIFY_CLIENT_ID and SPOTIFY_REDIRECT_URI.

Run server

    $ $(cd server ; python server2.py)


Connect to [http://localhost:8235/oraclex/](https://oraclex.zonenow.io/)  

Credit: Base of project from Sort Your Music project [https://github.com/plamere/SortYourMusic](https://github.com/plamere/SortYourMusic)
