For arbitrary metric space $(X,d)$, with two closed sets $A,B$, we have that their union $A\cup B$ is also closed.

**PROOF**: Take an arbitrary sequence $(c_n)\subseteq A\cup B$ such that $c_n\to c\in X$. Now, if both $A$ and $B$ are finite, then $(c_n)$ is eventually constant and the theorem holds trivially. Suppose then that at least one of $A$ or $B$ are infinite, and suppose it is $A$. Then $A$ must contain a subsequence $(a_n)$ of $(c_n)$ that is also infinitely long. If $B$ was also infinite, then either both $A$ and $B$ would contain infinite subsequences of $(c_n)$ or only one of them would. Either way, letting at least $A$ have such a subsequence tells us that, because of [[3MS.P5. Lemma - Subsequences share the Limit|the lemma]], this subsequence also converges to $c$. Hence, since $A$ is closed, $c\in A$. Hence $A\cup B$ is closed. QED.