Index: [[Index for 3TA Topics in Algebra]]

Prev: [[Index for 3TA Topics in Algebra]]

Next: [[3TA.2.]]

# Def: Partial order

A partial order on a [[Definition - Set|set]] $P$ is a [[Definition - Binary Relation|binary relation]] "$\leq$" on $P$ such that, $\forall~x,y,z\in P$, 

1. (Reflexive) $x\leq x$
2. (Antisymmetric) $x\leq y,~y\leq x~\Rightarrow~x=y$ 
3. (Transitive) $x\leq y,~y\leq z~\Rightarrow~x\leq z$

We say $x||y$ is $x$ and $y$ are incomparable.

A set $P$ coupled with a partial order $\leq$, is denoted $(P,\leq)$ and is called a partially ordered set ("poset"). We shall refer to $\mathcal{P}$ as the set of all posets.

# Def: Strict Order
$x<y~\equiv~x\leq y~\cap~x\neq y$

# Def: Inclusive Order
An **inclusive** order or **order by inclusion** is an order put on the [[Definition - Power Set|power set]] of a set. So, letting $X$ be a [[Definition - Set|set]] and $P(X)$ the [[Definition - Power Set|power set]] of $X$, define $$\forall A,B\subseteq X,~~~A\leq B~\Leftrightarrow~A\subseteq B$$ (Check that this is indeed an order)

# Def: Pre-Order

A pre-order is a partial order but without the antisymmetric axiom.

OR

A pre-order ("order") on a [[Definition - Set|set]] $P$ is a [[Definition - Binary Relation|binary relation]] "$\leq$" on $P$ such that, $\forall~x,y,z\in P$, 

1. (Reflexive) $x\leq x$
2. (Transitive) $x\leq y,~y\leq z~\Rightarrow~x\leq z$

# Def: Chains and Antichains
Let $(P,\leq)$ be a poset.

* $(P,\leq)$ is a **chain**, or linearly ordered set, or a totally ordered set when $$\forall x,y\in P,~~~x\leq y~~\text{or}!~y\leq x$$ That is, all elements are comparable. For example, $\mathbb{N}=\{1,2,3,\ldots\}$ with its usual order. A non-example is $(P(X),\subseteq)$ where $P$ is the [[Definition - Power Set|power set function]].
* $(P,\leq)$ is an **antichain** iff $$\forall x,y\in P,~~~x\leq y~\Rightarrow~x=y$$ That is, no distinct elements are comparable. This is called the **discrete order**.
* We denote $\underline{n}$ as the $n$-element chain, that is, a chain with $n$ elements.
* We denote $\overline{n}$ the $n$-element antichain.
* Arbitrary set can be turned into a poset by imposing the discrete order.

Next: [[3TA.2.]]

Prev: [[Index for 3TA Topics in Algebra]]

Index: [[Index for 3TA Topics in Algebra]]