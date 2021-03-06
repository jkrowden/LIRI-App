# LIRI-App Node.js
This is a Node.js app that takes in commands and arguments and logs the results of the search/query.

## Installing
Prereq: [Have node installed](https://nodejs.org/en/);

1.Clone the repo

2.'npm init -y' within the root of the folder. 

3.'npm install --save' should install the modules you need

4.. You must create a .env file and provide your API keys to it. Copy and paste this code into .env and provide your keys where applicable:



###Spotify API keys
```
SPOTIFY_ID=[spotifyid]
SPOTIFY_SECRET=[spotify-secret-code]
```

###Twitter API keys
```
TWITTER_CONSUMER_KEY=[twitter-consumer-key]
TWITTER_CONSUMER_SECRET=[twitter-consumer-secret]
TWITTER_ACCESS_TOKEN_KEY=[twitter-access-token-key]
TWITTER_ACCESS_TOKEN_SECRET=[twitter-access-token-secret]
```

5 . in the 'param' variable at the beginning of the 'loadTweets' function, provide your (or another person's) username.

You should now be able to run the program!

# Commands
LIRI comes with some neat commands.
```
'my-tweets' - Displays your last 20 tweets. The username for this program should be provided by you, or it will default to a  fake account.
'tweets [arg]' - Displays the last 20 tweets of the provided Twitter username. Arg: twitter-username
'spotify-this-song [arg]' - Displays information of a song. Arg: song-name
'movie-this [arg]' - Displays some information about a movie/show/video game. Arg: movie
'do-what-it-says' - Runs the commands listed in the random.txt file. The commands can be edited with any of
    these commands in place seperated by a comma and a space, just like you see in the txt file. If the 
    argument is more than one word, use "quotes".
'help' - Displays a list of LIRI commands. No arg.
'history' - Displays a list of the last 20 commands that were used in LIRI. No arg.
```

## Screenshots
Here are some screenshots of LIRI in action!
![Different LIRI Commands](/LIRI-App/working.png?raw=true "LIRI 1");
![Do what it says](/LIRI-App/working2.png?raw=true "LIRI 2");

## Authors
jkrowden - [GitHub](https://github.com/jkrowden)

## Acknowledgement
I'd like to thank Mr. Bulldops for his contribution to the project

@bulldops22

I would also like to thank anyone who views or actually uses this project in anyway. Plz like and subscribe