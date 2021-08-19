Index: [[Index for 3TN Topics in Analysis]]

See: [[3TN. Sequence]], [[3TN. Limit of a Sequence]]

https://en.wikipedia.org/wiki/Limit_inferior_and_limit_superior

We say $$L_i=\liminf_{n\to\infty}x_n$$ when
$$L_i=\sup_{k\in\mathbb{N}}\inf_{n\geq k}x_n~\Leftrightarrow~\forall k\in\mathbb{N}~~\inf_{n\geq k}x_n\leq L_i~$$ $$\text{and}~\forall\varepsilon>0,\exists k_{\varepsilon}\in\mathbb{N}:~n\geq k_{\varepsilon}~\Rightarrow~L_i-\varepsilon<x_n$$

So the limit inferior is the supremum of the set of infimums $\{i_1, i_2,\ldots\}$ where $i_k$ is $\inf\{x_k, x_{k+1},\ldots\}$. Careful thought and inspection reveals that this is an important object.

% define limit superior similarly