README.md
Algoirthm 1 : Trick-Or-Trick House Wait Times 

This algorithm calculates how many houses you need to pass after each one to find a house with more candy. Given an array {houseCandies}, it returns an array {waitHouses} where each element shows the number of steps forward to reach a house with more candy—or 0 if none exists.
Example:  
Input:[3, 5, 8, 2, 1, 4, 10, 6]  
Output:[1, 1, 4, 2, 1, 1, 0, 0]

Algorithm 1 Test Bench:  Use the main() function as a test bench
1. Create House Objects
2. Use sample candy values like {1, -2, 3, 4} to build a chain of houses
3. Try the Methods
4. Use getCandy(n) to see how much candy you get from n houses
5. Use getMaxCandyOnStreet(n) to find where the most candy can be collected in n steps
6. Print the Results
7. Print out what the methods return so you can see if it looks right
