[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/QM7QGF1q)
# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Proof by counterexample: Suppose we have two graphs $G_1$ and $G_2$

$G_1$ = [$x_1$] - $E_{1,1}$ - [$x_2$] - $E_{1,2}$ - [$x_3$] ([] are nodes and - $E_{k,k} - are edges)

$G_2$ = [$y_1$] - $E_{2,1}$ - [$y_2$] - $E_{2,2}$ - [$y_3$]

We can then see if we can map these by making a bijection function $f$, where $f$ = $x_n \rightarrow y_n$, meaning any x of some number equals the y of the same number. 

Then 

$(x_1,x_2) \in E_{1,1}$ iff $(f(x_1),f(x_2)) \in E_{2,1}$

Substitute

$(x_1,x_2) \in E_{1,1}$ iff $(y_1,y_2) \in E_{2,1}$

Then

$(x_2,x_3) \in E_{2,2}$ iff $(f(x_2),f(x_3)) \in E_{2,2}$

Substitute

$(x_2,x_3) \in E_{2,1}$ iff $(y_2,y_3) \in E_{2,2}$

So $G_1$ is isomorphic to $G_2$ 

$\therefore$ Since $G_1$ and $G_2$ are both not completely connected graphs and we can see they pass the definition of isomorphism, any two graphs that are isomorphic don't have to be completely connected. 
