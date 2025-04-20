README.md
Algoirthm 1 : Trick-Or-Trick House Wait Times 

This algorithm calculates how many houses you need to pass after each one to find a house with more candy. Given an array {houseCandies}, it returns an array {waitHouses} where each element shows the number of steps forward to reach a house with more candy—or 0 if none exists.
Example:  
Input:[3, 5, 8, 2, 1, 4, 10, 6]  
Output:[1, 1, 4, 2, 1, 1, 0, 0]

Algorithm 1 Code Explanation: 

This Algorithm models a series of connected houses, each holding a number of candies
The House class includes constructors to create a single house or a linked list from a list of values, automatically setting negative values to zero
The getCandy(int n) method calculates the total number of candies from the current house over n steps, while getMaxCandyOnStreet(int n) identifies the best starting point to collect the most candy within n houses 
The main() function showcases how these features work through sample runs.
