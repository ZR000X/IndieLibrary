Index: [[Index for ZR000 Quantum Complexity]]

A unitary operator $\hat{U}$ is an operator whose [[3QC. Adjoint|adjoint]] is equal to its inverse, that is,
$$\hat{U}^\dagger=\hat{U}^{-1}~~\Leftrightarrow~~\hat{U}^\dagger\hat{U}=\hat{U}\hat{U}^{\dagger}=\mathbb{1}$$

# Property 1
The product of two unitary operators is again a unitary operator.

PROOF: Let $\hat{U},\hat{V}$ be unitary and let $\hat{W}=\hat{U}\hat{V}$. Observe:
$$\hat{W}\hat{W}^{\dagger}(\hat{U}\hat{V})^\dagger(\hat{U}\hat{V})=\hat{V}^\dagger \hat{U}^\dagger \hat{U}\hat{V}=\mathbb{1}$$

You easily obtain $\hat{W}^{\dagger}\hat{W}=\mathbb{1}$ as well, and hence $\hat{W}$ is unitary. QED.

# Property 2
The modulus of the eigenvalues of a unitary operator must be $1$.

PROOF: Let $$\hat{U}\ket{\lambda}=\lambda\ket{\lambda}$$ Applying the modulus of both sides, $$||\hat{U}\ket{\lambda}||^2=||\lambda\ket{\lambda}||^2=\bra{\lambda}\lambda^*\lambda\ket{\lambda}=|\lambda|^2\braket{\lambda|\lambda}=1$$
if we assume eigenvectors are kept normalised.

# Property 3
$$\hat{U}\ket{\lambda}=\lambda\ket{\lambda}~\Rightarrow~\bra{\lambda}\hat{U}=\lambda\bra{\lambda}$$

PROOF: $$\ket{\lambda}=\mathbb{1}\ket{\lambda}=\hat{U}^\dagger\hat{U}\ket{\lambda}=\lambda\hat{U}^\dagger\ket{\lambda}$$
$$\therefore \ket{\lambda}=\lambda\hat{U}^\dagger\ket{\lambda}$$
$$\Rightarrow\bra{\lambda}=\lambda^*\bra{\lambda}\hat{U}$$
$$\Rightarrow\lambda\bra{\lambda}=|\lambda|^2\bra{\lambda}\hat{U}$$

And since $|\lambda|=1$, we are done.

# Property 4
Distinct eigenvectors of unitary operators are orthogonal.

PROOF: 
