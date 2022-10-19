What its about: Transfer your apple music library to spotify. 

How its done: Request a user's apple music library and save it to a file locally. Then, read from that file and make a best effort to like the same song on spotify. Then, generate a report about what songs were added/not found. 

Set up: Have to set up dev tokens for both apple music and spotify. Save them to the .env file locally. Run script.

Apple music API documentation: https://developer.apple.com/documentation/applemusicapi
Spotify API documentation: https://developer.spotify.com/documentation/web-api/reference/#/