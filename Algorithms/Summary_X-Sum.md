# Symmary: X-Sum Problem
X-Sum problem refers to a category of problems that try to find X numbers in a sequence that add up to a given target number.
The required results may be the indices of the X numbers, tuples of the X numbers, the number of all the tuples, etc.

There are sereval common approaches to solving these problems.

## 1.Brutal search

Maybe this is the most straightforward way to solve X-Sum problem. 
It just tries all the posssible combinations of X numbers in the given sequence, and compares the sum with the target number.

The time-complexity is O(n^X).

Although it is easy to come up with and implement, this approach is inefficient.

## 2.Binary search

First, we have to sort the sequence. 
Then, we can try all the combinations of X-1 numbers, and use binary search to look for the last number in the rest of the sequence.

The time-complexity is O(n^(X-1)*logn).

This approach reduces the cost of inner search from O(n) to O(logn). However, it requires a sort operation before search, 
which usually has a time-complexity O(n*logn). In 2-Sum problem, it is not the optimal solution in terms of time-complexity.

## 3.

## 4.