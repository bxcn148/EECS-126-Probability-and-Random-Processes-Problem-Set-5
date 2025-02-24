Download link :https://programming.engineering/product/eecs-126-probability-and-random-processes-problem-set-5/


# EECS-126-Probability-and-Random-Processes-Problem-Set-5
EECS 126: Probability and Random Processes Problem Set 5

1.

Midterm

Solve all of the problems on the midterm again (including the ones you got correct).

2. Convergence in Probability

Let (Xn)n1=1, be a sequence of i.i.d. random variables distributed uniformly in [ 1; 1]. Show

that the following sequences (Yn)n1=1 converge in probability to some limit.

n

(a) Yn = Qi=1 Xi.

(b) Yn = maxfX1; X2; : : : ; Xng.

(c) Yn = (X12 + + Xn2)=n.

3.

Gambling Game

Let’s play a game. You stake a positive initial amount of money w0. You toss a fair coin. If it

is heads you earn an amount equal to three times your stake, so you quadruple your wealth.

If it comes up tails you lose everything. There is one requirement though, you are not allowed

to quit and have to keep playing, by staking all your available wealth, over and over again.

Let Wn be a random variable which is equal to your wealth after n plays.

Find E[Wn] and show that limn!1 E[Wn] = 1.

Since limn!1 E[Wn] = 1, this game sounds like a good deal! But wait a moment!! Where does the sequence of random variables fWngn 0 converge almost surely (i.e. with probability 1) to?

4. Twitch Plays Pokemon

You wake up one day and are surprised to see that it is 2014, when the world was peaceful. You immediately start playing Twitch Plays Pokemon. Suddenly, you realized that you may be able to analyze Twitch Plays Pokemon.

You

Stairs

Figure 1: Part (a)

The player in the top left corner performs a random walk on the 8 checkered squares and the square containing the stairs. At every step the player is equally likely to move to any of the squares in the four cardinal directions (North, West, East, South) if there is a square in that direction. Find the expected number of moves until the player reaches the stairs in Figure 1.


[Hint: Use symmetry to reduce the number of states in your Markov chain]
