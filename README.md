# algorithm-intuitions
Intuitions about algorithms and data structures

### Divide and Conquer
#### Array Rotation
  Problem - Given an array of n integers, rotate it by d positions to the left/right.
  
  Solution - Rotate the array one by one for until d iterations
  
  Improved solution - Instead of rotating one by one, divide the array in different sets
  where number of sets is equal to GCD of n and d and move the elements within the sets.
  
  **Intuition** - Whenever a solution starts to feel sequential, there's a good chance that the problem can be broken down into smaller subproblems and the solution to the original problem would be the combination of the solutions of the subproblems.
  
