## Activity Set 2

 1. Given an array, find the int that appears an odd number of times. There will always be only one integer that appears an odd number of times.
 
 2. Some numbers have funny properties. For example:

89 --> 8¹ + 9² = 89 * 1

695 --> 6² + 9³ + 5⁴= 1390 = 695 * 2

46288 --> 4³ + 6⁴+ 2⁵ + 8⁶ + 8⁷ = 2360688 = 46288 * 51

Given a positive integer n written as abcd... (a, b, c, d... being digits) and a positive integer p

we want to find a positive integer k, if it exists, such as the sum of the digits of n taken to the successive powers of p is equal to k * n.
In other words:

Is there an integer k such as : (a ^ p + b ^ (p+1) + c ^(p+2) + d ^ (p+3) + ...) = n * k

If it is the case we will return k, if not return -1.

Note: n and p will always be given as strictly positive integers.

3.  Create a range function that accepts the following parameters.
   - start
   - limit
   - stride

 The stride or the increment is an integer that represents the difference between two
 consecutive values in the series.

Calling range(0, 10, 1) should give the output: 0 1 2 3 4 5 6 7 8 9 
Calling range(0, 10, 2) should give the output: 0 2 4 6 8 


4. Create a range function that accepts the following parameters.
   - start
   - count
   - generator
  The generator is a function that return a value for a given index in the series.

  Count is the value of the (last index + 1 ) of the series.

  For example, if your generator takes input x and returns x^2, and your count is 10, and the start is say 1, then your output series should be, 1 4 9 16 25 36 49 64 81 100

5. Write a program that accepts n numbers, and outputs the same.

Sample Input
123, 34, 543, 34, 453
Sample Output
123, 34, 543, 34, 453

(The size will not be given. Output should not be immediate, it should be after pressing "Enter" key)
