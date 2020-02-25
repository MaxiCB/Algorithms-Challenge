#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) The running time of this snippet is Linear 0(n) - while a < n3 (n cubed) we add n2 (n squared) to a
The function in essence id doing (n2 * n) which is equal to n3 so the amount of times it runs is equal
to n

b) The running time of this snippet is Linear 0(n) - the function depends on for i in range(n) which will
run n times


c) The running time of this snippet is Linear 0(n) - this function will recurse until bunnies = 0
bunnies will always reach 0 after n operations. return 2 + bunnyEars(bunnies-1) will happen at the same
rate of the input

## Exercise II

To determine the floor f I would iterate over all numbers until a egg is broken, then subtract 1

for i in n
drop egg from i
if egg == broken
    return i -1
    
The runtime complexity of this would be Linear 0(n) - This is because the chance that f could be equal 
to n in some cases
