Let $(X,d)$ be some metric space and let $B[a,r]\subset X$ be a closed ball centred at $a\in X$ with radius $r$. Then $B$ is closed.

PROOF: We have $$B[a,r]=\{x\in X:d(a,x)\leq r\}$$

Consider any arbitrary limiting sequence $(x_n)$ where all $x_n\in B$. This means every $x_n$ obeys $$d(a,x_n)\leq r$$

Say $x_n\to x$. We simply want to show that $x\in B$ follows. Observe,
$$0\leq d(a,x)\leq d(a,x_n)+d(x_n,x)\leq r+d(x_n,x)$$

Sending $n\to\infty$ we see
$$d(a,x)\leq r+0$=r$$
$$\therefore x\in B$$

QED.

