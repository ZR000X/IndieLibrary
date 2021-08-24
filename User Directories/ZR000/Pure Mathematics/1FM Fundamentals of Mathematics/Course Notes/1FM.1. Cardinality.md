Index: [[Index for ZR000 1FM Fundamentals of Mathematics]]

Prev: [[Index for ZR000 1FM Fundamentals of Mathematics]]

Next: [[1FM.2. Comparing Cardinalities]]

See: Hammack 14.1.

---

# Cardinality

Q: When is $|A|=|B|?$

Let $A$ be a finite set. Then $|A|$ is the number of elements inside of $A$. e.g., $|\{0,1,2,3\}|=4$. So, for finite sets, they have equal cardinality if they have the same number of elements.

But a problem arises when considering infinite sets. We seek a different notion of counting in this case, that is, a different way to assign a "size" to a set. The solution is to redefine cardinality such that it satisfies the finite case but can be applied to the infinite case. The solution is about 1-1 mappings. The definition of cardinality is [[1FM. Definition - Cardinality|here]].

Q: $|\mathbb{N}|=|\mathbb{Z}|$?. Yes. (Exercise)

Q: $|\mathbb{N}|=|\mathbb{R}|$?. No. Georg Cantor proved this to be impossible using what is known as the [Cantor Diagonal Argument]

We now show that the equality of cardinality is an [[1FM. Definition - Equivalence Relation|equivalence relation]]. We do that in this proposition. Then we define the [[1FM. Definition - Cardinal Numbers|cardinal numbers]].

---

**EXERCISE**: show that $|(0,\infty)|=|(0,1)|$. It can be shown that, by drawing the interval $(0,1)$ vertically, starting from a point $(0,0)$ up to a point $(0,1)$, then drawing a horizontal line from position $(-1,0)$ out to positive infinity, intersecting $(0,0)$, that any point $(x,0)$ can be connected to the point $(-1,1)$ by a line that intersects the vertically drawn interval at some point $(0,f(x))$, and that, using similar triangles, $$f(x)=\frac{x}{1+x}$$

It remains to be clear that this formula for $f(x)$ is a bijection. Hence, once that is clear, it is also clear that $f:(0,1)\to(0,\infty)$. QED.

**EXERCISE** You can now show that $|\mathbb{R}|=|(0,\infty)|$ as well. Simply use the bijection $e^x:\mathbb{R}\to(0,\infty)$. Hence, as well, by transitivity, $|\mathbb{R}|=|(0,1)|$.

**EXERCISE** You can now show that $|\mathbb{R}|=|(a,b)|$ for all real numbers $a,b$, $a<b$. Simply use the bijection $$h(x)=a(1-x)+bx$$

---

# Why's $|\mathbb{N}|$ special?

Consider $\mathbb{N}$. We can list the naturals in a sequence, each natural taking a finite time to reach, if one is "counting" at any non-zero pace. This property is not enjoyed by "uncountable" sets such as $\mathbb{R}$. This prompts a definition of [[1FM. Definition - Countably Infinite etc.|countably infinite]] and other terms.

We have a [[1FM.P3. Theorem - Countable means Listable|theorem]]. Convince yourself that:

* $|\mathbb{N}|$ is countable.
* $|\mathbb{Z}|$ is countable.
* $|\mathbb{Q}|$ is countable. (Exercise)
* $|\mathbb{R}|$ is uncountable.

We have another [[1FM.P4. Theorem - Unions of Countable are Countable|theorem]] which states that the union of two countably infinite sets is again countably infinite.

---

# More on Cardinal Numbers
Any finite number $n\in\mathbb{N}$ can be thought of as a cardinal number representing the cardinality of all sets $S$ such that $|S|=n$. But then we think of the cardinal number $|\mathbb{N}|=\aleph_0$ See [[1FM. Cardinal Number|the definition]] and [[1FM.P5. Theorem - Cross Product of Aleph0 is Aleph0|the following theorem]], which allows us [[1FM.P6. Corrollary - The Rationals are Countable|this corollary]] that the rationals are also countably infinite.

---

Index: [[Index for ZR000 1FM Fundamentals of Mathematics]]

Prev: [[Index for ZR000 1FM Fundamentals of Mathematics]]

Next: [[1FM.2. Comparing Cardinalities]]




