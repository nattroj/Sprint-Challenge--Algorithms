#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) o(n)


b) o(n)


c)

## Exercise II

1. Start at floor n / 2 and mark as temp_f.  


2. If the egg breaks, go to floor temp_f / 2.  Repeat until egg doesn't break and mark this floor as safe_f. 


3. Increment up by (temp_f - safe_f) / 2. Continue until egg breaks again. If egg does break, repeat 2nd and 3rd step until reaching f

algorithm is similar to binary search, will give it an approximate complexity of: o(log n)