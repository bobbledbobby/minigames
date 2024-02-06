# Snooplab Minigames

## Rules
All server-specific community guidelines apply.
Follow the [Snooplab Guidelines](https://github.com/snooplab/snooplab_rulestos).
No teaming up. Exceptions given to Discord Among-Us
Do not leave mid game: this means leaving you're about to get eliminated. It's considered cheating.
## Basic Commands
**/host [type-of-game]** Host a game, required option of the type of game.

Bot will send a message to a logging channel. 
An Administrator will then have to go to the Integration settings and enable “/participate” 
Bot will do @Minigames Ping asking people to join the queue.
Bot will generate and log the Game ID.

**/participate [game-pass]** Participate in a game. Game password required.

At least 3-5+ people are needed to continue with a game.
If 3-5 people did not join the game, Admins will be asked to override “/participate”
When 3-5+ people join the queue (within 1 minute), the game will start.

**/blacklist [user] [reason]** Blacklist a user from joining a game
**/leave** Leave the queue (or game)

## Simon Says
No teaming up.
Minimum: 3 players
Duration: until 1 player (and Simon) remains

- /ask-custom Repeat a command through the bot (Simon only)
- /automatic Generate an automatic prompt and eliminate the user.
- Simon says person below gets eliminated
- Simon says person below gets to choose someone to lose
- Simon says answer: what is (insert basic math question)
- Simon says answer: what is (insert question)
- Answer: what is (insert question)
**/report-bug** Report a found bug using that when used the command /automatic, a bug was found

/eliminate Eliminate a user from game
/cheater [cheater] Bot will send a message to logging channel asking moderators to check if a user has cheating by deleting a message to not get eliminated
/answer-auto Answer an /automatic question.


## Discord Gartic Phone
Max 4 people.
No teaming up.
Duration: anywhere to 3 minutes 50 seconds. 

User 1, 4 (referenced as team 1)  will start drawing (1:30 minutes)
User 2, 3 (referenced as team 2) will start drawing (1:30 minutes)
Team 1 will guess Team 2’s drawings (10 seconds)
Team 2 will guess Team 1’s drawings (10 seconds)
Host will be asked to run /reveal whenever they’re ready, they have 10 seconds.
Players has 20 seconds to look at reveals.

/draw [link] Insert a link of a drawing. Must be an imgur, or discord attachment.
/my-word DMs the user saying what they are supposed to draw.
/guess [drawing-id] Guess a drawing.
/reveal Reveal guesses, answers and drawings.’


## Guess The ? (Manual Game)
**/send-form** Send the form

Bot will send a form, asking:
Option 1: “attachment”: Go to Google, search for something like “harry potter” or somewhere similar, copy the link and paste it in the “option 1” thing.
Option 2: what the attachment is (you’ll have to say what the attachment is, in this case put in “harry potter”
Bot will send option 1 into chat.
Players will need to guess what it is. If it is correct, they get a point. Game Leaders will have to keep track of points.

**/guess** Guess the “option 1”

When everyone guessed, admins will have to do /send-form or /end-round.

**/end-round** End the round.

When everyone guessed, admins will have to do /send-form or /end-round.

## Discord Among-Us
Max 7 people.
2 roles.
**How it works**: There are 2 roles. Crewmates & Impostors. 
You are not allowed to reveal your role. You may pretend to be a crewmate, whose objective is to eliminate the impostors by running _/EMERGENCYMEETING!11_.

**/status** Reveal your role.
**/unalive** Kill a CREWMEMBER.

- The chosen crewmember will be unalived.
- The bot will send a message to the channel when someone has been unalived.
**/EMERGENCY-MEETING!!11** Suspect someone?
**/confess-anonymously [message]** Send a message in the channel as the bot
