# The 3n+1 Problem
Consider any positive integer $n$. Then let $$f(n)=\left\{\begin{matrix}n/2 & n\equiv 0\mod{2}\\ 3n+1 & n\equiv1\mod{2}\end{matrix}\right.$$

Define an iterative mapping 
$$
	f^{(k)}(n)=f^{(k-1)}(n),~~~f^{(0)}(n)=n
$$
$$
	n_k=f^{(k)}(n),~~~n_0=n
$$

What is known as the Collatz Conjecture is the following,
$$\forall n\in\mathbb{Z},n>0,~~~\exists k:~~~n_k=f^{(k)}(n)=1$$

This problem remains unproven.