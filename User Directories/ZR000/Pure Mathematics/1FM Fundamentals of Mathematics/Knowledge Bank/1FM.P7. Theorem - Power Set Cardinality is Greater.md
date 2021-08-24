Index: [[Index for ZR000 1FM Fundamentals of Mathematics]]

Return: [[1FM.2. Comparing Cardinalities]]

See: [[1FM. Definition - Cardinality#More generally]]

For all non-empty sets $A$, we have $$|A|<|\mathcal{P}(A)|$$ where $\mathcal{P}(A)|$ is the [[KB_The Power Set|power set]] of $A$.

**PROOF**: In the case of $A$ finite, we have $|\mathcal{P}(A)|=2^{|A|}>|A|$. In all other cases, showing there exists an injection $A\to\mathcal{P}(A)$ and that $|A|\neq|\mathcal{P}(A)|$ would be enough. The injection $A\to\mathcal{P}(A)$ is trivial: define 
$$f:A\to\mathcal{P}(A),~~~~~f(a)=\{a\}$$
which is that $f$ sends each $a\in A$ to the singleton set $A\supseteq\{a\}\in\mathcal{P}(A)$. The other condition for injectivity is one-to-one: and indeed we have $$\{a\}=\{b\}\Leftrightarrow a=b$$ 

We now just need to show there is no bijection $g:A\to\mathcal{P}(A)$. It is sufficient to show that $g$ cannot be surjective. To do so we need only find some $B\in\mathcal{P}(A)$ such that $\forall a\in A$, $g(a)\neq B$, and that such a $B$ will exist for all conceivable $g$.

Let $x\in A$ be arbitrary. Either $x\in g(x)$ or $x\notin g(x)$. Now for the ingenious reveal. We define
$$B=\{x\in A: x\notin g(x)\}$$

The idea is similar as that in Russell's Paradox. We have some $a\in A$. In the case of $a\in g(a)$, we have that $a\notin B$, and so $B\neq g(a)$. In the only other case of $a\notin g(a)$, then $a\in B$, and again $B\neq g(a)$. Since these are all possibilities, we always have $B\neq g(a)$. Since such a set $B$ clearly always exist for all possible $g$, we have that $g$ cannot be surjective.

QED.

Q: Does this not feel like too much trickery? When did we use any property of the power set when showing there is no bijection? Is there no bijection between any pair of members of a more general family of sets?