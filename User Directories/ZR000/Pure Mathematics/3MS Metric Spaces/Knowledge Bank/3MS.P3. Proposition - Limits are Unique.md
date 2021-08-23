Let $(x_n)$ be a sequence in some metric space $(X,d)$ and suppose that $x_n\to x$ and $x_n\to y$ as $n\to\infty$, where $x,y\in X$. Then $x=y$.

PROOF: Observe $$0\leq d(x,y)\leq d(x,x_n)+d(x_n,y)$$

Taking $n\to\infty$, this becomes $$0\leq d(x,y)\leq d(x,x)+d(y,y)=0$$
$$\therefore d(x,y)=0~~\Leftrightarrow~~x=y$$

QED.