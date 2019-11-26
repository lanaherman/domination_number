# domination_number

The following conjecture is proposed that relates the k-rainbow total domination number γkrt
and the usual domination number γ. As it is mentioned in the previous project, the k-rainbow
total domination number can be defined as γkrt(G) = γt(G  Kk), where γt stands for the total
domination number.
Conjecture 3. For a graph G and k ≥ 4, we have the tight bound γkrt(G) ≥ 2γ(G).
The purpose of this project is to test that the conjecture with possibility of disproving it. We
can start with k = 2 and increase it by 1 in each step. For each such k, test the conjecture for
all “small” graphs; for “large” graphs, apply some trajectory metaheuristic method disitinct from
simulated annealing. Try going with k as large as possible. For larger value of k, try to find
graphs G for which we have equality γkrt(G) = 2γ(G), otherwise propose how the constant 2 can
be replaced with something larger as k increases. Separately test bipartite graphs and trees.
