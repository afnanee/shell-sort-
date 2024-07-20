the time complexity of shell sort depends on the gap sequence h1, h2, h3,..., hn

there is no ready to use formula to get the complexity for all gap sequences, but we used the shell original formulation which is :
 In the first pass, the gap is n\2, then n\4 , then n\8, until the last pass where the gap is 1 

the best case :

the array is already sorted, so the time complexity is O(nlog(n))
the outer loop runs log(n) times
 the inner loop runs n times   = O(nlog(n))

 the average case :
 the while loop will exit in the middle

the time complexity is O(nlog(n)^2)

 the worst case :

the array is in reverse order
so the time complexity is O(n^2)
because the inner loop may need to iterate multiple times for each iteration of the outer loop.
