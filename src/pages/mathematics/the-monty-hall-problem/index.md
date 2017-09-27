---
title: The Monty Hall Problem
---
## The Monty Hall Problem

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/mathematics/the-monty-hall-problem/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->

#### More Information:
<!-- Please add any articles you think might be helpful to read before writing the article -->


# The Monty Hall Problem

The Monty Hall Problem is a counter-intuitive puzzle based on _Probability._ 

## The Puzzle:

Suppose you're on a game show, and the host of the game `Monty` has given you the choice to select "ONE" of the three doors. Whichever door you will select and open, you will get the prize behind that door.
 
 * Behind one door is a car and behind the others have a goat each. You are not aware of which door conceals what but the host "Monty" knows.
 
 * You will select one door and before opening that door, the host will open one of the other two doors which contains a goat.

* The host will give you a second chance to think about your choice. -" _` To Swap `_ to the other unopened door." or "  _`To Stick`_ to the same door".


### QUESTION :

What you should choose - _"To Swap"_ or  _"To Stick"_  to maximize your chances of winning the car?

 
## General Misconception:

It seems like "Swap" or "Unswap" does not make any difference. As the host has already shown the one goat, therefore the other two doors conceal one goat and one car. Selecting any one will have a 50-50 probability or 1/2 probability of selecting a car. (Selecting one out of two choices).

However this is not correct!!!

## Correct Solution :

We should always select _`TO SWAP`_ .Because it has twice the probability of winning a car.

Here is the illustration:

**No Swap (_`TO STICK`_)** :

There can be two cases in this:

Case 1 : Selecting a goat in the first round with a probability of 2/3 . (Selecting a goat out of 2 goats and 1 car) and then `No swap` 

Case 2 : Selecting a car in the first round with a probability of 1/3 . (Selecting a car out of 2 goats and 1 car) and then `No swap` 

```Therefore chance of winning a car by choosing not to swap is 1/3.```

**To Swap :**

There can be two cases in this:

Case 1 : Selecting a goat in the first round with a probability of 2/3 . (Selecting a goat out of 2 goats and 1 car) and then `To Swap`
Swapping will lead you to win the car (As the other unopened door will surely conceal the car).

Case 2 : Selecting a car in the first round with a probability of 1/3 . (Selecting a car out of 2 goats and 1 car) and then `To Swap` 
Swapping will lead you to the goat (As the other unopened door will surely conceal the goat).

```Therefore chance of winning a car by swapping is 2/3.```

So, We should always ` Swap ` to maximize our chance of winning a car.

  

