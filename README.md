# PrimeFactorAttack
Educational Game for 4th Grade Math Students written in Java

TODO (add more items or place your name on things you want to do):<br>
1) Replace the blocks (that now are simple colored rectangles) with some more interesting graphic.
    The colors must stand out form the background and the numbers on the blocks must be clearly readable.

2) Add background images to levels past 3.

3) Greatly improve transition screens.

4) Greatly improve bonus level games/add new games.  
   Jarek:  I plan to add a new bonus level (that extends BonusLevel.java) in which a player must avoid composite 
   numbers entering the screen at random locations.  The player is given ammunition consisting of the prime numbers im
   the initial number's prime factorization.  When the player shoots a composite number with a divisible prime number,
   the prime number will be shown inside of the block drawn for the composite number.  If the player successfully his 
   the composite number with all of the values in its prime factorization, the ammunition used will be dropped by the 
   composite number block.  New composite number monsters will be spawn in addition to prime number ammunition.  
   If the player hits a composite number monster with a prime number that is not divisible, the composite number will
   increase in size based on a difficulty factor.
   
   (I plan on creating a new bonus level as well. I'll probably squeeze it in directly after the first level is finished, as to give the kids an opportunity to play it. I'm not sure how far in the game they will get. The bonus level I'm thinking of doing is something similar to the Space Invaders arcade game. -Josh Rhodes)

5) Different button styles at different levels.                                                                              
   Josh: I plan to change the look of the buttons after every bonus level. For instance, the first 5 levels will be the black buttons at the beginning of the game then the buttons will have a different look on levels 6-10, 11-15, etc. until you reach the end of the game.

6) 1 IS NOT A PRIME!!!  A prime number is a natural
   number ***greater than 1*** that has no positive divisors other than 1 and itself! 

7) Theme shift: Many of the explosions are both nice looking and mathematical. I think
   it would be nice to add "famous mathematicians" theme that ties all the levels together.
    I would like to see a few of the main classic dudes featured
    (i.e. Euclid, Newton, Pythagoras, Archimedes, Euler, Turing, Hypatia, Ada Lovelace, Florence Nightingale)
    but with a greater number of modern
    mathemagicians (https://en.wikipedia.org/wiki/Category:21st-century_mathematicians).
    For example, the background images could be low contrast bust superimposed on abstract
    landscapes that include symbols and elements of the depicted mathematician's work.
    One level could have 5 or 6 different but related backgrounds so in one game,
    one background is shown
    and in a different game at the same level a different background is shown.

8) Different sound effects or each level. Not sound effects that you find on the web,
   but sounds that you create and record yourself.
   Jaehee: I already changed that sound when I shoot the number(original sound:fireworks.wav -> changed sound: sand.wav)
   And I plan to make this sound as various versions sounds for each level.
   Chase: I will add sound effects to when the user gives a bad input, a sort of shrieky sound, and other 
          sorts with my Viola, trumpet, clarinet etc...

9) Chase: When a user gets 10 in a row correct all of the boxes on the bottom of the screen explode and a bonus
   level automatically starts, perhaps randomly selected from the bonus levels already implemented. At the
   conclusion of the bonus level, the game resumes as it was before. 


