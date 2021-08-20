Index: [[Index for ZR000 Quantum Complexity]]

See: [[3QC. Classical Hamiltonian]], http://www.physics.usu.edu/Wheeler/QuantumMechanics/QM16SHOQuestions.pdf

So we have the classical Hamiltonian
$$H=\frac{1}{2m}p^2+\frac{m\omega^2}{2}x^2$$

Notice that
$$\left(x+\frac{ip}{m\omega}\right)\left(x-\frac{ip}{m\omega}\right)=x^2-\frac{1}{m^2\omega^2}p^2$$
which is quadratic in both position and momentum, and turns out to be but a factor away from the classical Hamiltonian.
$$\left(x+\frac{ip}{m\omega}\right)\left(x-\frac{ip}{m\omega}\right)=\frac{2}{m\omega^2}H$$

The brackets happen to be conjugates of one another as well, so we define two operators $\hat{a},\hat{a}^*$ to be these brackets as well as each containing the square root of the factor.
$$\hat{a}=\sqrt{\frac{m\omega}{2\hbar}}\left(\hat{X}+\frac{i\hat{P}}{m\omega}\right)$$
$$\hat{a}^\dagger=\sqrt{\frac{m\omega}{2\hbar}}\left(\hat{X}-\frac{i\hat{P}}{m\omega}\right)$$
where we did not bore you with knowing $A$ in advance. Instead, we will now compute $A$ such that the mentioned equality holds. Note that unlike before, we not have guaranteed commutativity between all the terms. It is this we must now take into account in the computation.

As an exercise, show that
$$\hat{H}=\hbar\omega\left(\hat{a}^\dagger\hat{a}+\frac{1}{2}\right)$$
where $[\hat{X},\hat{P}]$ is the [[3QC. Ring Commutator|commutator]] between $\hat{X},\hat{P}$, which from the [[3QC. Uncertainty Principle|uncertainty principle]], specifically the [mechanics interpretation](https://en.wikipedia.org/wiki/Uncertainty_principle#Matrix_mechanics_interpretation), we have $[\hat{X},\hat{P}]=i\hbar\mathbb{1}$ given to us. 

See the other properties in the linked webpage.