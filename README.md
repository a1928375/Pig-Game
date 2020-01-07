# Pig-Game

1. Pig Game: Write a function, play_pig, that takes two strategy functions as input, plays a game of pig between the two strategies, and returns the winning strategy. 

    Play a game of pig between two players, represented by their strategies. Each time through the main loop we ask the current player for     one decision, which must be 'hold' or 'roll', and we update the state accordingly. When one player's score exceeds the goal, return         that player.

2. Doubling Pigs: In this problem, we introduce doubling to the game of pig. At any point in the game, a player (let's say player A) can offer to 'double' the game. Player B then has to decide to 'accept', in which case the game is played through as normal, but it is now worth two points, or 'decline,' in which case player B immediately loses and player A wins one point. Your job is to write two functions. The first, pig_actions_d, takes a state (p, me, you, pending, double), as input and returns all of the legal actions.

      The second, strategy_d, is a strategy function which takes a state as input and returns one of the possible actions. This strategy         needs to beat hold_20_d in order for you to be marked correct.
