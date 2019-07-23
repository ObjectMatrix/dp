### Memoization, Tabulation  

There are at least two main techniques of dynamic programming which are not mutually exclusive:

## Memoization  
This is a laissez-faire approach: You assume that you have already computed all subproblems and that you have no idea what the optimal evaluation order is. Typically, you would perform a recursive call (or some iterative equivalent) from the root, and either hope you will get close to the optimal evaluation order, or obtain a proof that you will help you arrive at the optimal evaluation order. You would ensure that the recursive call never recomputes a subproblem because you cache the results, and thus duplicate sub-trees are not recomputed.

## Tabulation  
You can also think of dynamic programming as a "table-filling" algorithm. This is like memoization but more active, and involves one additional step: You must pick, ahead of time, the exact order in which you will do your computations. This should not imply that the order must be static, but that you have much more flexibility than memoization.

## conclusion   
Simply saying top down approach uses recursion for calling Sub problems again and again where as bottom up approach use the single without calling any one and hence it is more efficient.