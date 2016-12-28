# InstaScraper
A webscraper to get around Instagram's API requirements.

The purpose of the webscraper is simple.

With an initial user given, this webscraper creates a list of their followers (to a specified depth) and adds the unique usernames to a queue.
The initial user is removed from the queue and the process repeats for the next user in the queue (which will be the first follower of the initial user).
This process is repeated a specified number of times.
Repeat users are not added back into the queue.
