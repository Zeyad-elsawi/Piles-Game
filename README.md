You are supposed to implement a game, where one of the players is the computer and the other is a human.
We are having three bags 1, 2, 3. Each player takes turn and removes between 1 and 5 objects from one of three
bags. The player who removes the last object(s) wins the game. Here are the rules:
• Each bag contains 10 objects in the beginning of the game.
• The first turn is for the human then comes the computer’s turn.
• The player can remove object(s) from a single bag at a time
• The player can not choose to remove 0 objects.
• The number of objects has to be between 1 and 5 (inclusive).
• The player has to enter the bag first (1 or 2 or 3) and then the number of object(s) that have to be removed
from that bag.
• You have also to check whether the human’s input is valid. Is it a valid bag (1 or 2 or 3)? Is it a valid number
of objects (between 1 and 5)? Also are there enough objects in the bag? If any of these conditions are not
met, then the user should be asked for an input again (bag and number of objects).
• Note that you need to make sure that the computer’s selection should be always valid. The computer’s turn
should not end unless it guessed a correct bag ( containing at least 1 object) and a valid number of objects
from that bag. Once the computer guesses the correct bag and number of objects the human has the turn to
play.
• The computer should never guess an invalid bag nor invalid number of objects to be removed.
• The game ends when all bags are empty.
• The player who removes the last object wins the game.
