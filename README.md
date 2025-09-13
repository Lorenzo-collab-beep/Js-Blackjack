This Blackjack Trainer is a casino-style European blackjack game designed to practice card counting. 
Player follows standard rules while improving strategy and tracking cards to maximize their chances of winning.

Original project I used for reference ((https://bmeinert8.github.io/is-blackjack/)) by Brian Meinert see 
(https://dev.to/bmeinert8/javascript-blackjack-51d2)

PURPOSE:

    This game allows you to train your card counting skills\!\!\!
    The configuration is hardcoded, you can change it at the top of main.js...
    At default you get 8 decks and a random cut between the middle and the end minus 1/2 deck.
    If you change decks number the strategy might be different, so make sure to update it here:
        \--\>    (https://www.beatingbonuses.com/bjstrategy.php)
    When the deck is over the game shaffles and even the cut position changes.

RULES (The most common rules in real european casinos):

    \- Make you bet and try to reach 21, but be careful to not bust!
    \- Double allowed only on hard hands between 9 and 11.
    \- Max split: 3 times.
    \- If you split aces you can do it only 1 time, you get a card for each hand and you can not hit anymore.
    \- You cannot double after a split.
    \- The dealer does not check for BJ
    \- Split allowed on the same value for example (2, 2), (10, 10), (10, K) ...
    \- House Edge (0,77-0,78)%.
