# Coin Sequence Problem
from Workable ([original post](http://buff.ly/1Rip3b0))

## Description
Suppose we have 4 coins, each with a different probability of throwing Heads. An unseen hand chooses a coin at random and flips it 50 times. This experiment is done several times with the resulting sequences as shown below (H = Heads, T = Tails) Write a program that will take as input the data that is collected from this experiment and estimate the probability of heads for each coin.

## Data
The data is stored as coinproblem.txt

## Solution
I used a MLE method for this one. The first-cut code is in coinsoln_old.jl, which was later updated to coinsoln.jl with automatic differentiation. 
