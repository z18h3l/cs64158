java c
Fair Allocations
COMP 4418 – Assignment 3
Due 14 November 2024, 16:00
Total Marks: 100
Late Penalty: 10 marks per day
Worth: 15% of the course
Question 1 (20 marks)    Consider a fair division instance ⟨N,M, v⟩ with n agents and m items. Prove or disprove the following:
1.  (5 marks) Any Pareto Optimal allocation must also be Leximin Optimal.
2.  (5 marks) Given any two allocations, one must pareto dominate the other.
3.  (5 marks) For n = 2, any allocation that satisfies PROP is also EF.
4.  (5 marks) Greedy round robin algorithm will return an EF1 allocation.
Question 2 (20 marks)    Consider the following instance with n = 4 and m = 8.

g1
g2
g3
g4
g5
g6
g7
g8
v1
1
5
4
4
0
1
1
1
v2
5
9
5
5
0
0
5
5
v3
5
7
5
10
0
4
0
5
v4
10
10
5
5
5
5
5
5For this instance, consider running the standard round robin algorithm to find an EF1 alloca- tion. We shall look at how different orderings over agents can lead to different allocations. For the given instance, identify:
1.  (10 marks) The ordering over agents which leads to the following allocation: A = (A1 ,A2 ,A3 ,A4), whereA1 = {g1 , g5}, A2 = {g4 , g8}, A3 = {g3 , g7} andA4 = {g2 , g6}.
2.  (5 marks) An alternate EF1 allocation that can result from the same ordering which would Pareto dominate A.
3.  (5 marks) An alternate ordering for the standard round robin algorithm that would result in the allocation identified in the previous part.

Question 3 (20 marks)    Consider an indivisible item setting with m > n where agents are indifferent between the items. That is, f代 写COMP 4418 – Assignment 3 Fair AllocationsProlog
代做程序编程语言or any i ∈ N and g  g′  ∈ M, we have that vi(g) = vi(g′) > 0. However, agent valuations are not identical. That is, for i  j, vi(g)  vj(g). For this setting:
1.  (5 marks) Show that an MMS allocation always exists.
2.  (5 marks) Show that an EF1 allocation will always be MMS.
3.  (10 marks) Give examples of instances in this setting such that:
a.  Any allocation with maximum ESW is not MMS.
b.  There is at least one allocation with maximum USW which is 2/1−MMS in this instance.
Question 4 (20 marks)    Consider the random assignment problem with 3 agents with the following preferences over 3 items.≻1:   g1  ≻ 1 g2  ≻1 g3 ≻2:    g1  ≻2 g2  ≻2 g3 ≻3:    g2  ≻3 g1  ≻3 g3
Find the random assignment as a result of the following rules.
1.  (10 marks) probabilistic serial (PS)
2.  (10 marks) random serial dictator (RSD)
Question 5 (20 marks)    Consider the following instance with n = 4 and m = 8.

g1
g2
g3
g4
g5
g6
g7
g8
v1
1
5
4
4
0
1
1
1
v2
5
9
5
5
0
0
5
5
v3
5
7
5
10
0
4
0
5
v4
10
10
5
5
5
4
1
1
Consider the allocation A in which A1  = {g1 , g2}, A2  = {g3 , g4}, A3  = {g5, g6}, and A4 = {g7 , g8}.
1.  (5 marks) Prove or disprove that the allocation is envy-free.
2.  (5 marks) Prove or disprove that the allocation is envy-freeable.
3.  (5 marks) Compute the corresponding envy-graph with the amount of envy on the edge weights.
4.  (5 marks) Find the subsidy needed to be given to each agent in order to make the allocation envy-free or show that no such subsidy exists.



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
