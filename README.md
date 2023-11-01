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

I have two graphs they are called A and B, these are isomorphic which means there exists a function f that is bijective one-to-one 
and onto that map goes both directions. Because of these additional properties above, two graphs $A$ and $B$ have the same number of nodes that are completely connected and are also isomorphic. For example:

Graph A: has two nodes A and B, they are completely connected as follows

A____B


Graph B: has two nodes C and D, they are also completely connected as follows.

C____D

Both graphs A and B have two nodes, they are completely connected. Because of bijective properties, both one-to-one and onto mapping in bidirectional. So, they are isomorphic.
