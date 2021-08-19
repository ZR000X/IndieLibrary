Index: [[Index for 3TN Topics in Analysis]]

Return: [[3TN.1. Sequences]]

See: [[3TN. Sequence]], [[3TN. Limit of a Sequence]]

Let $(x_n),(y_n)$ be two real sequences. If their limits are $L_1,L_2$ respectively, and for large $n$ we have $x_n\leq y_n$, then $L_1\leq L_2$ follows.

PROOF: Assume the contrary that $L_1>L_2$ (and they are finite). We know that for any positive $\varepsilon$ we have $$|x_n-L_1|<\varepsilon~~~\text{and}~~~|y_n-L_2|<\varepsilon$$
for large $n$.

Choosing $\varepsilon<\frac{1}{2}(L_1-L_2)$, which is positive by assumption, we than have
$$L_1\varepsilon<x_n\leq y_n<L_2+\varepsilon$$ for large $n$.

But this implies $$0<L_1-L_2<2\varepsilon$$ which is in contradiction with our choice: $\varepsilon<\frac{1}{2}(L_1-L_2)$ implies $2\varepsilon<L_1-L_2$. QED.