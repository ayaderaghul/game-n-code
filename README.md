# game-n-code
*I want you to teach yourself game theory in a programming language, by coding the exercise in your own native lang (i.e. lang you feel at ease to express your self). I write in Racket/Scheme (LISP) and some other langs I am learning. Contribute your own solution and feel free to speak up if you see something deserved to be said*

## Nash equilibrium
*The best way to convey the message is probably through an example. The details are chosen carefully to transmit a substantial amount of knowlege.*

Nash equilibrium is an intuitive concept. Consider my way of explaining it here and see how well it goes with your intuition. This is the semantic way of teaching fundamental concepts in game theory and in evolved (programming) languages.

This chapter has three parts: to explain the theory, to explain it in code (here comes my solution), and your own solution. You can see that this lesson needs you to be/feel completed. I would pay my part of the bargain. I wish you to bring yours and yourself to the table.

Let's start with example 0: the Prisoner's Dilemma game. The reason each chapter revolves around a typical example is so that you can absorb the theory easily by hearing the story it tells.

The game has two players p1, p2 sharing two strategies s1, s2. If the outcome is (s1, s1), the payoff is (2, 2). Similarly, the outcome (s2, s2) mapped to the payoff (-1, -1). When the outcome is (s1, s2), the equivalent payoff vector is (0, 4). With outcome (s2, s1), the payoff is (4, 0). Here is the tabular representation of the game:

p1\p2    |  s1   |  s2
-------------------------
s1       | 2, 2  | 0, 4
-------------------------
s2       | 4, 0  | 1, 1



...tba...
