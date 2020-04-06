# SkipList-Analysis
 The implemented skip list follows a coin-flip strategy. For a coin flip, it is promoted to next level only if the coin
comes up heads. In this implementation coin flip is actually a fixed probability p whose value is 0.5. The node
keeps getting promoted until it is less than probability p. After inserting each key in the skip list, we kept on
counting the elements in each level to observe the distribution of elements when the number of keys is larger.
The graph was plotted with of L1/L0, L2/L0, …, Ln/L0. In this case, maximum levels are 10 i.e. 0 to 9. It can be
seen as each successive insert in the skip list starts to converge, at each level, as the number of insertions starts
growing. It is observable in graph that L1/L0 converges around ½ of the elements w.r.t to level 0 (keeping in mind
that all insertion will present in bottom level), whereas L2/L0 converges around ¼ and later levels are half of its
above i.e. 1,1/2,1/4,1/8 and so on.
Provided graphs shows that each insertion for a probability distribution in the skip list.
