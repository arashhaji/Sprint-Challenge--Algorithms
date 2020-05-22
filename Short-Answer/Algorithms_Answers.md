#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) this code block increases in a linear fashion also increases `n` ------> `O(n)`


b) `J` affects the inner loop of code block and the doubling of `n`  this would be equal to `log n`, the outer loop also increases in a linear fashion in regards to `n` so the two combined ----> `0(n*log n)`


c) `recursive` function until it hits `0`, value of bunnies. -------> `O(n)`

## Exercise II

Suppose that you have an n-story building and plenty of eggs. Suppose also that an egg gets broken if it is thrown off floor f or higher, and doesn't get broken if dropped off a floor less than floor f. Devise a strategy to determine the value of f such that the number of dropped + broken eggs is minimized.

Write out your proposed algorithm in plain English or pseudocode AND give the runtime complexity of your solution.

# Binary Search Tree 
# Time complexity is O(log(n)) reducing the amount of time because we are not looping through each of them 

1. egg breaks at first floor 
2. drop egg at floor 1
3. have a variable that will return (called it egg_broke)
4. define the range
5. find floors that is next to each other 
6. the egg broke or does not brake
7. set numbers that wont be in the way 
8. drop egg at middle floor 
9. if the egg breaks we are above floor f
10. update the variable that tracks lowest floor egg breaks 
11. if the egg does not break we are below floor f or at floor f 
12. update the variable that tracks highest floor egg breaks 
13. keep dropping eggs until we get to the highest floor where the egg is not broken that is 1 floor 


finding floor (n) then if egg broke return 0

    start equal 0
    end equal  n
    middle eguals (start plus end) then divide by 2

    high floor is not broke equals -20
    low floor broke equals 2 times 100

    while (high floor is not broke minus low floor broke) not equal minus 1:
        if egg broke then egg broke  equal Yes
        else egg broke equal No

        if egg broke end equal middle minus 1 
        if middle is less than low floor broke then low floor broke equals middle 
        middle equals (start plus end) divide by 2 
        else start equals middle plus 1 

        if middle is higher to the highest floor is not broken then highest floor is not broken equals middle
        middle equals (start plus end) divide by 2

        return highest floor is not broken 





