---
## Introduction
The famous Riemann hypothesis is closely related to the distribution of primes. In graph theory, by defining prime paths, a graph is said to be Ramanujan if and only if its Ihara zeta function satisfies an analogy of the Riemann hypothesis. This concept was origionally introduced by Toshikazu Sunada in 1985 and developed by A.A.Terras and H.M. Stark.

###  Prime Path of Graph
For a connected, finite graph $X$, its edges can be labeled as $(e_1,e_2,...,e_m)$, $e_{m+1}=e_1^{-1}$ and $e_{2m}=e_m^{-1}$, where $m=|E(X)|$ is the non-oriented edeges, and $e_j^{-1}=e_{j+m}$ denote opposite orientation. Then, we can define paths $C=(a_1,a_2,...,a_n)$, where $a_i$ is an oriented edge of $X$, there exist a $backtracking$ if $a_{i+1}=a_i^{-1}$, the path is said to have a $tail$ if $a_{n}=a_1^{-1}$. The path $C$ is a $closed$ $path$ or a $cycle$ when it consists of vertices $(v_1,v_2,...,v_m=v_1)$, and the closed path is $primitive$ if it has no tail or backtracking and $C\neq{D^f}$ for $f>1$, meaning the path is only allowed once.

For a closed path $C$, the $equivalence$ $class$ $[C]$ is defined as 
$[C]=\lbrace{a_1}\cdot \cdot\cdot{a_n},{a_2}\cdot\cdot\cdot{a_n},{a_n}{a_1}\cdot\cdot\cdot{a_{n-1}}\rbrace$,
two paths are called $equivalent$ if one can be obtained from the other by changing the starting vertex. 
A $prime$ in $X$ is an equivalence class $[C]$ of prime paths, the path length is the edge count $v(C)=n$.

<p align="center"><img src= "https://user-images.githubusercontent.com/66701331/187326050-c8d93df8-d35c-4b4f-a9e4-c5ef29b08945.png" width="200" height="180"> <p/>
<p align="center"> Arbitrary orientation for $(e_1,e_2,e_3,e_4,e_5)$ </p>

The Ihara zeta function is computed by the product over the equivalence class of prime paths. In Fig.1, some examples of primes are $[C]=\lbrace{{e_2}{e_3}{e_5}\rbrace,$ $[D]=\lbrace{e_1}{e_2}{e_3}{e_4}\rbrace,$ and $[E]=\lbrace{e_1}{e_2}{e_3}{e_4}{e_1}{e_{10}}{e_4}\rbrace.$
Here, $e_10={e_5}^{-1} is the backtracking, the path lengths are $v(C)=3$, $v(D)=4$, $v(E)=7$, respectively. In this case, there are infinitely many primes.


<p align="center"><img src= "https://user-images.githubusercontent.com/66701331/187325623-ef6c34c3-656e-4ffc-b173-2135757965ce.png" width="120" height="110"> <p/>
<p align="center"> n-cycle graph</p>

<p/>
<script type="text/javascript" charset="utf-8" src=" https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML, https://vincenttam.github.io/javascripts/MathJaxLocal.js"></script>
