# Analysis:

# [Task 0](Task0.py):
 • Time Complexity - O(1)
 • This algorithm is constant time because has a running time independent of the input size

# [Task 1](Task1.py):
 • Time Complexity - O(n)
 • This algorithm is linear time because even though it has two separate for-loops that 
   are dependant on the input, each one iterating from 1 to n, these result in O(2n) which 
   in turn, following the Big-O coefficient rule of dropping constants(coefficients in Big-O 
   are negligible with large input sizes), result in the time complexity being simplified to O(n)

# [Task 2](Task2.py):
 • Time Complexity - O(n)
 • This algorithm is linear time because it has one for-loop that iterates from 1 to n which 
   results in a running time grows directly in proportion to n.

# [Task 3](Task3.py):
 • Time Complexity - O(nlog(n))
 • This algorithm is superlinear time because even though it has two separate for-loops that 
   are dependant on the input, each one iterating from 1 to n, resulting in O(2n); it also has 
   a sorting function which is 0(nlogn). Combining these two results in 0(2n + nlogn). 
   However following the Big-O rule of dropping non-dominant terms (less dominant terms in Big-O are 
   negligible with large input sizes), the time complexity can be simplified to O(nlog(n))
   
# [Task 4](Task4.py):
 • Time Complexity - O(nlog(n))
 • This algorithm is superlinear time because even though it has two separate for-loops that 
   are dependant on the input, each one iterating from 1 to n, resulting in O(2n); it also has 
   a sorting function which is 0(nlogn). Combining these two results in 0(2n + nlogn). 
   However following the Big-O rule of dropping non-dominant terms (less dominant terms in Big-O are 
   negligible with large input sizes), the time complexity can be simplified to O(nlog(n))
