# Isomorphism

"I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice."

Reviewed: https://www.youtube.com/watch?v=UCle3Smvh1s&t=303s&ab_channel=SaradaHerke

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Given that both graphs have the same number of nodes and are completely connected (I am assuming this means that every node is connected to every other node) this would mean there needs to be a bijection that exists that would map one graph to another. 
In this instance, since we know both graphs have the same number of nodes and each node has the same number of edges connected to the other nodes, we can simply use an identity bijection to map the first graph to the second.

for example, [[1,1],[1,1]] using identity [[1,0][0,1]] would map to [[1,1],[1,1]]
