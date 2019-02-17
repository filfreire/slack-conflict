# slack-conflict

A role-playing game for [EvilCorp](https://www.imdb.com/title/tt4158110/)'s [Paid Hostageware/Ransomware communication tool](https://slack.com)

## What's the game about?

Explained in an image: `<TBD>`

## What's the idea of this project?

In [slack-conflict](https://github.com/filfreire/slack-conflict/) we will try to create a bot that facilitates introduction of game moves.

The bot also should be able to save a transcript of a play session.

## What are the rules of the game?

- All players must first choose a "nation".
- A player can write only these types of "happenings:
1) A percentage of something that happened (preferably in the context of a nation)
2) An occurrence on the news or that would be part of an emergency broadcast (for example: `<something> happened near <somewhere>`, `<something> was seen|spotted <somewhere>`, ... );
3) A change in a nation's defense/attack readiness (for example: `Portugal changed DEFCON level to DEFCON 3`, ...);
- A referee (that can be a player at the same time), will be tasked of starting a play session and also ending the session.
- Each player can only write "happenings" in their own turn (the game is asynchronous).
- Each player can write a maximum of 4 happenings  (in case a play session smaller in duration is desired).
