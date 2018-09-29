# pong-secure

Okay so first off don't expect this program to work. If you want to see a working version, run the non-secure "pong" on my page. I think the database and login stuff works, but scoring when logged in doesn't. And I don't think I did the api key right. And also the game ends after 1 score.

---

Now featuring a login, sort of. Register with a password. Login with the same username and password. Guaranteed to not be stored plain-text.

After entering two different names (names must be longer than one character), click on the "Start!" to play. For the left paddle, use W and S to move the paddle up and down. For the right paddle, use the up arrow and down arrow. You'll have lots of fun.

The game ends when one player has scored 25, er, 1 point. The leaderboard displays player names with the most wins. If you want, you can enter the top player's name and pretend you're them.

This was assigned in my CS class in 2017.

# Features

FUN pong game. Score updates automatically. Game movement is done entirely in JavaScript and has some movement physics.

Leaderboard updates automatically based on the names of winners. Data is stored with SQL.

Password salts and hashes. Api key so that you need to try a little harder to fake inputs.

# Credits

Teacher: Brian Sea from the Head-Royce School

# Author

Nathan Yuen

# License

GPL 3.0 2018
