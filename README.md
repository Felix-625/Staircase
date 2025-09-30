# Staircase

This C# program prints a right-aligned staircase pattern based on a user-provided integer n. The program starts by reading an integer n from the console, which represents the height of the staircase.The staircase method inside the Result class is responsible for generating and printing the pattern. It uses a for loop that runs from 1 to n, where each iteration corresponds to one level of the staircase.
For each level i: It first prints a number of spaces equal to n - i. This aligns the staircase to the right by pushing the # characters to the right side.Then, it prints i number of # characters, which increase with each level, starting from 1 at the top to n at the bottom.
The combination of spaces and # characters on each line creates the staircase shape visually aligned to the right.Finally, the Main method calls this staircase method with the input value n, displaying the staircase pattern on the console.
