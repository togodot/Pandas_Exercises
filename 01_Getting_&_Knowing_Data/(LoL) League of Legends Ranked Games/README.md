data > https://www.kaggle.com/datasnaek/league-of-legends

## About Dataset

### General Info
This is a collection of over 50,000 ranked EUW games from the game League of Legends, as well as json files containing a way to convert between champion and summoner spell IDs and their names. For each game, there are fields for:  

- Game ID  
- Creation Time (in Epoch format)  
- Game Duration (in seconds)  
- Season ID  
- Winner (1 = team1, 2 = team2)  
- First Baron, dragon, tower, blood, inhibitor and Rift Herald (1 = team1, 2 = team2, 0 = none)  
- Champions and summoner spells for each team (Stored as Riot's champion and summoner spell IDs)  
- The number of tower, inhibitor, Baron, dragon and Rift Herald kills each team has  
- The 5 bans of each team (Again, champion IDs are used)  

This dataset was collected using the Riot Games API, which makes it easy to lookup and collect information on a users ranked history and collect their games. However finding a list of usernames is the hard part, in this case I am using a list of usernames scraped from 3rd party LoL sites.

### Possible Uses
There is a vast amount of data in just a single LoL game. This dataset takes the most relevant information and makes it available easily for use in things such as attempting to predict the outcome of a LoL game, analysing which in-game events are most likely to lead to victory, understanding how big of an effect bans of a specific champion have, and more.
