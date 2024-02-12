# Snooplab Minigames

## Rules
All server-specific community guidelines apply.
Follow the [Snooplab Guidelines](https://github.com/snooplab/snooplab_rulestos).
No teaming up. Exceptions given to Murder Mystery.
Do not leave mid game: this means leaving you're about to get eliminated. It's considered cheating.

## Commands & Info
## Basic Commands
/host [type-of-game] Host a game, required option of the type of game.

Bot will send a message to a logging channel. 
An Administrator will then have to go to the Integration settings and enable “/participate” 
Bot will do @Minigames Ping asking people to join the queue.
Bot will generate and log the Game ID

/participate [game-id] Participate in a game. Game ID required.

At least 3-5+ people are needed to continue with a game.
If 3-5 people did not join the game, Admins will be asked to override “/participate”
When 3-5+ people join the queue (within 1 minute), the game will start.
 
“Hello,
Thank you for playing Minigames! You’ve successfully entered the queue.”
“Hello,
There has been an error trying to get into the queue.
Please contact a Game Leader, although this might be a client side and they might not be able to help you with it.
Thank you for playing Minigames.”


/blacklist [user] [reason] [appeal] [(show)] Blacklist a user from joining a game
“Hello,
There has been an error trying to get into the queue.
Please contact a Game Leader, although this might be a client side and they might not be able to help you with it.
Thank you for playing Minigames.”
“Hello,
It appears that you’ve been banned from Minigames for [reason]. Contact a Game Leader to get this issue figured out.”
“Hello,
It appears that you’ve been banned from Minigames for [reason]. Appeal your ban @ []”
“Hello,
It appears that you’ve been banned from Minigames for [reason].”

/leave Leave the queue or game

/say [text] Say something as a bot.
The bot will say [text]


## Simon Says

/ask-custom Repeat a command through the bot (Simon only)
/automatic Generate an automatic prompt and eliminate the user.
Simon says person below gets eliminated
Simon says person below gets to choose someone to lose
Simon says answer: what is (insert basic math question)
Simon says answer: what is (insert question)
Answer: what is (insert question)
 	/report-bug Report a found bug using that when used the command /automatic, a bug was found

/eliminate Eliminate a user from game
/cheater [cheater] Bot will send a message to logging channel asking moderators to check if a user has cheating by deleting a message to not get eliminated
/answer-auto Answer an /automatic question. 



## Discord Gartic Phone

Bot will DM User 1, 4 (referenced as team 1 what they are supposed to draw.
Team 1 will start drawing (1:30 minutes)
Bot will DM User 2, 3 (referenced as team 2) what they are supposed to draw.
Team 2 will start drawing (1:30 minutes)
Bot will DM user 1 user 2’s drawings. (10 seconds)
Bot will DM user 2 user 4’s drawings. (10 secs)
Bot will DM user 2 user 4’s drawings. (10 secs)
Bot will DM user 1 user 2’s drawings. (10 secs)
Team 2 will guess Team 1’s drawings (10 secs)
Host will be asked to run /reveal whenever they’re ready, they have 10 seconds.
Players has until host runs /end-the-chaos.

/draw [link] Insert a link of a drawing. Must be an imgur, or discord attachment.
/guess [drawing-id] Guess a drawing.
/reveal Reveal guesses, answers and drawings.



## Guess The ? (Manual Game)

/send-form Send the form

Bot will send a form, asking:
Option 1: “attachment”: Go to Google, search for something like “harry potter” or somewhere similar, copy the link and paste it in the “option 1” thing.
Option 2: what the attachment is (you’ll have to say what the attachment is, in this case put in “harry potter”
Bot will send option 1 into chat.
Players will need to guess what it is. If it is correct, they get a point. Game Leaders will have to keep track of points.

/guess Guess the “option 1”

When everyone guessed, admins will have to do /send-form or /end-round.

/end-round End the round.

## Murder Mystery

"aight guys. 
/reveal-role Send a DM revealing your role.
/EMERGENCY-MEETING

/end-the-chaos [W/L] [4th_place] [3rd_place] [2nd_place] [1st_place] [prize_4] [prize_3] [prize_2] [prize_1]   “End the Minigames”

Well, that was a fun round.
Let’s declare the winners, shall we?
In 4th place, we have [4th_place]! Congrats! You’ll get [prize_4]!
In 3rd place, we have [3rd_place]! Congrats! You’ll get [prize_3]!
In 2nd place, we have [2nd_place]! Congrats! You’ll get [prize_2]!
And, for first place, drumroll please…
:drumroll: :drumroll: :drumroll: :drumroll:
In 1st place, we have [1st_place]]! Congrats! You’ll get [prize_1]!


“They were lying when they said this was a fun round. This was so L.”
Let’s still declare the winners, shall we?”
“In 4th place, we have [4th_place]! Congrats! You’ll get [prize_4]!”
“In 3rd place, we have [3rd_place]! Congrats! You’ll get [prize_3]!”
“In 2nd place, we have [2nd_place]! Congrats! You’ll get [prize_2]!”
“And, for first place, drumroll please…”
“:drumroll: :drumroll: :drumroll: :drumroll:”
“In 1st place, we have [1st_place]]! Congrats! You’ll get [prize_1]!”

“Thank you for playing Minigames!”

