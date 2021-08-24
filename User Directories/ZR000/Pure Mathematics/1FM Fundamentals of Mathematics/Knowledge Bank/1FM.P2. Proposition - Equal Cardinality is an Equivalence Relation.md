Index: [[Index for ZR000 1FM Fundamentals of Mathematics]]

Return: [[1FM.1. Cardinality]]

See: [[1FM. Definition - Equivalence Relation]]

Let $A,B$ be sets and consider $(A,B)\in R$ when $|A|=|B|$, where $R$ is some relation. Then this $R$ is an equivalence relation.

PROOF: (Reflexivity) It is clear that one can find a bijection that maps all of a set $A$'s elements to themselves (e.g., the identity bijection $i_A$ of $A$), hence $|A|=|A|$.

(Symmetry) Since bijections are symmetric, a bijection $f:A\to B$ implies a bijection $g:B\to A$, hence $|A|=|B|$ implies $|B|=|A|$ and vice versa. 

(Transitivity) If there is a bijection $f:A\to B$ and another bijection $g:B\to C$, then a composition $g\circ f:A\to C$ is a bijection as well, hence $|A|=|B|$ and $|B|=|C|$ indeed implies $|A|=|C|$.

QED.