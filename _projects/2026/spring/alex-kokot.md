---
mentor: Alex Kokot
title: Reinforcement learning for optimal game-theoretic strategies
prereq: Strong coding abilities, and an interest in solving mathematics with reinforcement learning
bestfor: Sophomore (2nd year), Junior (3rd year), or Senior (4th year or beyond)
numbermentees: 1
year: 2026
quarter: spring
mode: In-person
---

Two players are each given a full suit of cards (Ace - King, 13 cards) shuffled, and draw 7 of these cards. The game is segmented into 3 rounds, with the goal being to win 2 of the 3 rounds. It is randomly decided which player goes first, and they have the choice of playing a card or "passing". Next, the other player is allowed to respond also by either playing or "passing", and this repeats until both players "pass" [if no cards remain in hand then you are forced to pass]. At this time, the player with the largest score (sum of card ranks played) wins the round, and the next round begins, with both players drawing 3 additional cards, and the winner of the previous round playing first.

To study this problem, we will try an algorithmic approach, simulating this game, and training an algorithm to learn an optimal strategy. Key questions of interest will be (1) to what extent the player going first is disadvantaged in this set-up, and (2) how the game may be modified to be fair. Depending on the interest of the student, we will also consider (3) mathematical underpinnings of these questions, with the main question being if one can formally prove an optimal strategy for the game under various assumptions. It may also be of interest to (4) consider further extensions of the proposed game.

This game is closely related to classical examples such as Colonel Blotto and Goofspiel, and bonus points to any students that can recognize the modern analogue of this strategy game.