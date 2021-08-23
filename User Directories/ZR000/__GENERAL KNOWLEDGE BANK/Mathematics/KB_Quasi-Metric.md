See:
* [Wikipedia :: Metric # Quasi-Metric](https://en.wikipedia.org/wiki/Metric_(mathematics)#Quasimetrics)

Usages:
* [[3MS. Quasi-Metric]]

A **quasi-metric** on a [[KB_Set|set]] $X$ is a [[KB_Function|function]] $d:X\times X\to \mathbb{R}$ such that, $\forall x,y,z\in X$:

1. (Separation) $x=y~\Rightarrow~d(x,y)=0,~d(x,y)=0=d(y,x)\Rightarrow~x=y$
2. (Triangle Inequality) $d(x,z)\leq d(x,y)+d(y,z)$

Note that a quasi-metric is almost a [[KB_Metric and Metric Space|metric]], but does not have the symmetry property and therefore needs to have the separation modified such that $d(x,y)$ must be symmetrically zero ($d(y,x)=0$ as well) for $x=y$ to be implied.