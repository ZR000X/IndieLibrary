Index: [[Index for 3TA Topics in Algebra]]

Prev: [[3TA.1. Partial Order, Strict Order, Inclusive Order, Pre-Order, Chain, Antichain]]

Next: [[3TA.3.]]

# Def: Order Isomorphisms
For arbitrary $P,Q\in\mathcal{P}$ and some function $\psi:P\to Q$, we call $\psi$ an **order-isomorphism** iff
1. $\forall x,y\in P,~~~x\leq y$ in $P$ $\Leftrightarrow$ $\psi(x)\leq\psi(y)$ in $Q$.
2. $\psi$ is onto.

Also, if there exists some function $\psi:P\to Q$ where $\psi$ is an order-isomorphism, then $P$ and $Q$ are said to be order-isomorphic.

# Proposition 3TA.2.1
If $\psi:P\to Q$ is an order-isomorphism, then $\psi$ is $1\to1$, and is therefore a bijection.

PROOF: To show $1\to1$, we need that $$x=y~\Leftrightarrow~\psi(x)=\psi(y)$$ Suppose that $\psi(x)=\psi(y)$. This would imply $\psi(x)\leq\psi(y)$ as well as $\psi(y)\leq\psi(x)$ by reflexivity. Then $x\leq y$ and $y\leq x$ both follow by the isomorphism. Hence $x=y$ is implied by reflexivity. The converse is proven similarly.

# Exercise 3TA.2.2
Suppose we have some $\psi:P\to Q$ which is an order-isomorphism. We know by [[3TA.2.#Proposition 3TA 2 1|this]] that $\psi$ is a [[Definition - Injection, Surjection, Bijection|bijection]], and so it must have an inverse function $\rho=\psi^{-1}$ where $\rho:Q\to P$ and $\rho(b)=a\Leftrightarrow\ b=\psi(a)$, for aritrary $a\in P$, $b\in Q$.

The exercise is to 
1. Prove that $\psi$ is a [[Definition - Well-Defined|well-defined]] function from $Q$ to $P$.
2. $\rho$ is an order-isomorphism.

SOLUTION: For arbitrary $x\in P$, we can assume $\psi(x)\in Q$ is a well-defined mapping. Since $\psi$ is a bijection, we know that there is only one value for $x$ such that $\psi(y)=x$, for all $x\in P$. Therefore, we assign this value: $\rho(y)=x$. So it is well-defined.

To prove that $\rho$ is an order-isomorphism. Let $x_1,x_2\in P$ and $y_1,y_2\in Q$ be such that $\psi(x_1)=y_1$ and $\psi(x_2)=y_2$. Then we have $\rho(y_1)=x_1$ and $\rho(y_2)=x_2$. Now the following are equivalent. $$x_1\leq x_2~\Leftrightarrow~\phi(x_1)\leq\phi(x_2)$$ $$\rho(y_1)\leq\rho(y_2)~\Leftrightarrow~y_1\leq y_2$$

# Exercise 3TA.2.3
Consider the naturals $\mathbb{N}$ and the even naturals $\mathbb{E}$. Define a mapping $\psi:\mathbb{N}\to\mathbb{E}$ as $\psi(n)=2n$ for all $n\in\mathbb{R}$. You can show that this is an order-isomorphism fairly easily.

# Exercise 3TA.2.4
Think about the function $\psi:P\to Q$ such that $P=\{a,b,c,d\}$ and $Q=\{1,2,3,4\}$, $b\leq d$, $c\leq d$, $a\leq b$, $a\leq c$ and $1\leq2\leq3\leq4$, and $\psi(d)=4$, $\psi(c)=3$, $\psi(b)=2$, $\psi(a)=1$. You can show that $\psi$ is a bijection but not an order-isomorphism, and further that $P\to Q$ is not order-isomorphic (by contradiction).

# Exercise 3TA2.5
1. Argue that $\mathbb{N}$, $\mathbb{Z}$, $\mathbb{Q}$, $\mathbb{R}$ are all chains.
2. Prove that $\mathbb{N}$ and $\mathbb{Z}$ are not order-isomorphic. (Hint: $\mathbb{N}$ has a least-element)
3. 

Next: [[3TA.3.]]

Prev: [[Index for 3TA Topics in Algebra]]

Index: [[Index for 3TA Topics in Algebra]]