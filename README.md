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

Assuming I have two graphs they are called A and B. They all have three nodes and are completely connected. Graph A has nodes V1={a, b, c}. The set of edges E1={ab, bc, ca}. Graph B has nodes V2={d, e, f} with a set of edges E2={de, ef, fd}. Now considering there is a function f in Graph A start from the node a, then goes through b and c; and also this function f mapping in graph B can goes through from d, then e, finally f. So, this function mapping from one-to-one and onto. Because every relation possesses properties ${(u,v)} \in E_1 \iff {f(u),f(v)} \in E_2$. So, they are isomorphic.
