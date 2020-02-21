#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) The function iterates through n once, therefore  O(n).


b) The running time is O(n^2) because we have two nested loops.


c) An algorithm has ‘constant time’ when the number of operations doesn’t change as the number of elements increase. In the bunnyEars example, it doesn’t matter how many elements are contained in bunnies. However, the function is being called recursively n times before reaching base case so its O(n)



## Exercise II


This function is a recursive funtion and a three steps algorithm. Here are the steps: 
    1. Pick a pivot (f). 
    2. Partition the array of n elements into two sub-arrays: elements less than f and elements greater than f.
    3. Test if the egg will be broken if thrown  off at floor f
        a. if yes, call the function recursively on the elements less than f
        b. if no, call the function recursively on the element greater than f
    4. Keep the lower element 

