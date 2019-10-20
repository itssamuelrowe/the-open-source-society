## Activity Set 2

 1. GCD of more than two (or array) numbers
Given an array of numbers, find GCD of the array elements.

Examples:

Input  : arr[] = {1, 2, 3}
Output : 1

Input  : arr[] = {2, 4, 6, 8}
Output : 2
 
 2. John is very fond of horses. He enjoys watching them race. As expected, he has a stable full of horses. He, along with his friends, goes to his stable during the weekends to watch a few of these horses race. John wants his friends to enjoy the race and so he wants the race to be close. This can happen only if the horses are comparable on their skill i.e. the difference in their skills is less.

There are N horses in the stable. The skill of the horse i is represented by an integer S[i]. John needs to pick 2 horses for the race such that the difference in their skills is minimum. This way, he would be able to host a very interesting race. Your task is to help him do this and report the minimum difference that is possible between 2 horses in the race.

Input:
First line of the input file contains a single integer T, the number of test cases.
Every test case starts with a line containing the integer N.
The next line contains N space separated integers where the i-th integer is S[i].

Output:
For each test case, output a single line containing the minimum difference that is possible.
Constraints:
1 ≤ T ≤ 10
2 ≤ N ≤ 5000
1 ≤ S[i] ≤ 1000000000

Example:
Input:
1
5
4 9 1 32 13

Output:
3

Explanation:
 The minimum difference can be achieved if we pick horses with skills 1 and 4 for the race.

3.  Array of size n is given as input.
Print the nPr value and nCr value where nPr is permutation and nCr is combination.


4. Juggler Sequence
Juggler Sequence is a series of integer number in which the first term starts with a positive integer number a and the remaining terms are generated from the immediate previous term using the below recurrence relation :
 
Juggler Sequence starting with number 3:
5, 11, 36, 6, 2, 1

Juggler Sequence starting with number 9:
9, 27, 140, 11, 36, 6, 2, 1

Given a number n we have to print the Juggler Sequence for this number as the first term of the sequence.
Examples:

Input: 9
Output: 9, 27, 140, 11, 36, 6, 2, 1
We start with 9 and use above formula to get
next terms.

Input: 6
Output: 6, 2, 1