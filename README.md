[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12590783&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## Answer

Assume that both graphs have the same number of nodes and are fully connected. For every node in graph A, a unique node can be found in graph B without additional nodes. We have a function f: A <—> B, where the subscripts Va_i are equivalent to the subscripts Vb_i, denoted as Va1 ←→ Vb1, Va2 <---> Vb2, and so forth. In essence, I created arbitrary permutations of all nodes in the first graph and separately generated arbitrary permutations of all nodes in the second graph, subsequently mapping them accordingly. This means that there is a one-to-one relationship between the two graphs because both graphs have the same number of nodes. Furthermore, since the two graphs are fully connected, every pair of distinct vertices is connected by a unique edge. An edge between two specific nodes in graph A can also match an edge from a unique pair of nodes in graph B. Every edge in graph A can be mapped onto graph B since they have the same number of nodes. This can confirm that there is an ontological relationship between them, which can be expressed as $f: V_1 \rightarrow V_2$ such that $(u,v) \in E_a$ iff $(f(u),f(v)) \in E_b$. Therefore, if two graphs have the same number of nodes and are fully connected, they must be isomorphic.

