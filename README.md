---
# Introduction
The famous Riemann hypothesis is closely related to the distribution of primes. In graph theory, by defining prime paths, a graph is said to be Ramanujan if and only if its Ihara zeta function satisfies an analogy of the Riemann hypothesis. The concept of graph Riemann hypothesis was first introduced by A.A.Terras.
<p/>
The Ihara zeta function is used to describe a finitely connected regular graph $X$, defined as
$$\zeta_X\left(u\right)=\prod_{\left[C\right]}{({1-u^{v\left(C\right)})}^{-1}},$$
where $u$ is a sufficiently small complex number, and the infinite product is over all $[C]$ of primes in $X$.
<p/>
For a connected, finite graph $X$, its edges can be labeled as $(e_1,e_2,...,e_m)$, $e_{m+1}=e_1^{-1}$ and  $e_{2m}=e_m^{-1}$, where $m=|E(X)|$ is the non-oriented edeges, and $e_j^{-1}=e_{j+m}$ denote opposite orientation.
The graph theory version of the prime number theorem can be defined as
$$\pi(m)\sim{\frac{\Delta{X}}{mR_{X}^{m}}},$$
for $R_{X}$ is the radius of convergence and $\pi(m)$ is the number of primes counted less than or equal to $m$. Then the graph Riemann hypothesis $[2]$ asserts that the Ihara zeta function
$\zeta_X\left(u\right)$
is pole free for
$$R_X<|u|<\sqrt{R_X}.$$

A path $C=(a_1,a_2,...,a_n)$, where $a_i$ is an oriented edge of $X$, is said to have a $backtrack$ if $a_{i+1}=a_i^{-1}$, for $i=(1,...,n-1)$, and the path is said to have a $tail$ if $a_{n}=a_1^{-1}$. The path $C$ is a $closed$ $path$ or a $cycle$ when it consists of vertices $(v_1,v_2,...,v_m=v_1)$, and the closed path is $primitive$ if it has no tail or backtracking and $C\neq{D^f}$ for $f>1$, meaning the path is only allowed once.

For a closed path $C$, the $equivalence$ $class$ $[C]$ is defined as $[C]=\big\{{a_1}\cdot \cdot\cdot{a_n},{a_2}\cdot\cdot\cdot{a_n},{a_n}{a_1}\cdot\cdot\cdot{a_{n-1}}\big\}$, two paths are called $equivalent$ if one can be obtained from the other by changing the starting vertex. 
A $prime$ in $X$ is an equivalence class $[C]$ of prime paths, the path length is the edge count $v(C)=n$.


<p/>
<script type="text/javascript" charset="utf-8" src=" https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML, https://vincenttam.github.io/javascripts/MathJaxLocal.js"></script>
