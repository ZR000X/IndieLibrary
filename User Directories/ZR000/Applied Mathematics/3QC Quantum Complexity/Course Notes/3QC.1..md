Index: [[Index for ZR000 Quantum Complexity]]

# [arXiv:2001.08664](https://arxiv.org/abs/2001.08664) Cosmological Complexity

Take a Hamiltonian $$\hat{H}=\frac{1}{2}\hat{p}^2-\frac{1}{2}k^2\hat{x}^2$$
which is an inverted harmonic oscillator.

Using the raising and lower operators such that
$$\hat{x}=\frac{1}{\sqrt{2k}}(\hat{a}^\dagger+\hat{a}),~~~~~\hat{p}=i\sqrt{\frac{k}{2}}(\hat{a}^\dagger-\hat{a})$$
the Hamiltonian easily becomes
$$\hat{H}=-\frac{k}{2}(\hat{a}^2+{\hat{a}^{\dagger}}^2)$$

...

---
# [arXiv:1905.13534](https://arxiv.org/abs/1905.13534) Chaos and Complexity in Quantum Mechanics

Consider the Hamiltonian
$$H=\frac{1}{2}p^2+\frac{\Omega^2}{2}x^2$$
where $\Omega^2=m^2-\lambda$.

* $\lambda<m^2$ describes a [simple harmonic oscillator](https://en.wikipedia.org/wiki/Harmonic_oscillator).
* $\lambda>m^2$ describes an inverted oscillator.
* $\lambda=m^2$ is a [free particle](https://en.wikipedia.org/wiki/Free_particle).

The case of $\lambda>m^2$ is of interest. The inverted oscillator can be considered a model for short-time approximations of unstable or chaotic systems. Particularly, we find exponential sensitivity to the initial conditions, a trait of chaotic systems.

The initial state, or reference state, of $\psi(x,t)$ is, for our purposes,
$$\psi(x,0)=\mathcal{N}_0\exp\left(-\frac{1}{2}\omega_0 x^2\right)$$ where $$\omega_0=m$$ 

The general state is given by
$$\psi(x,t)=\mathcal{N}(t)\exp\left(-\frac{1}{2}\omega(t) x^2\right)$$
where $\mathcal{N}(t)$ is the normalization factor and $\omega(t)$ is an important quantity to calculate.

Consider
$$\ket{\psi(t)}=e^{-iHt}\ket{\psi_0}$$
where $e^{iHt}$ is the evolutionary operator on an initial, or reference, state $\ket{\psi_0}$ to a target state $\ket{\psi(t)}$.

The quantity $\braket{x|\psi(t)}$ is the projection of $\ket{\psi(t)}$ onto the $x$ dimension, giving the coordinate $\psi(x,t)$.
$$\psi(x,t)=\braket{x|e^{-iHt}|\psi_0}$$
$$=\bra{x}e^{-iHt}\int dx'\ket{x'}\braket{x'|\psi_0}$$
$$=\int dx'\bra{x}e^{-iHt}\ket{x'}\braket{x'|\psi_0}$$
since
$$\int dx'\ket{x'}\bra{x'}=1$$
(Why>>>?)

We rewrite this as
$$\psi(x,t)=\int dx'K(x,t;x',0)\psi_0(x')$$
where
$$K(x,t;x',0)=\bra{x}e^{-iHt}\ket{x'}$$
$$=\left(\frac{\omega_1}{i2\pi\sin(\omega_1 t)}\right)^{1/2}\exp\left\{\frac{i\omega_1}{2}\left[\left(x^2+x'^2\right)\cot(\omega_1 t)\right]-\frac{2xx'}{\sin(\omega_1 t)}\right\}$$
(Why>>>?)

Note as well that
$$\psi_0(x')=\psi(x',0)=\mathcal{N}_0\exp\left(-\frac{1}{2}\omega x'^2\right)$$
as previously stated.

We can now perform the computation. The integral we want to compute, which is what we obtain when substituting these large expressions into the expression for $\psi(x,t)$ and then removing constants and combining exponents, is
$$I=\int dx'\exp\left\{\frac{i\omega}{2}\left[\left(x^2+x'^2\right)\cot(\omega t)\right]-\frac{2xx'}{\sin(\omega t)}-\frac{1}{2}\omega x'^2\right\}$$
which actually still contains removable constants,
$$\exp\left(-\frac{i\omega}{2}x^2\cot(\omega t)\right)I=\int dx'\exp\left\{\frac{i\omega}{2}x'^2\cot(\omega t)-\frac{2xx'}{\sin(\omega t)}-\frac{1}{2}\omega x'^2\right\}$$

Focusing on this integral,
$$I'=\int dx'\exp\left\{\left(i\cot(\omega t)-1\right)\frac{\omega}{2}x'^2-\frac{2xx'}{\sin(\omega t)}\right\}$$

Using [[3QC. Gaussian Integral Identity|this general result]], we can solve this immediately,
$$I'=\left(\frac{2\pi}{\omega(1-i\cot{(\omega t)})}\right)^{1/2}\exp\left(\frac{2x^2}{\omega\sin^2(\omega t) (1-i\cot(\omega t))}\right)$$

Reequating this to the above,
$$I=\left(\frac{2\pi}{\omega(1-i\cot{(\omega t)})}\right)^{1/2}\exp\left(\frac{i\omega}{2}x^2\cot(\omega t)\right)$$ $$\exp\left(\frac{2x^2}{\omega\sin^2(\omega t) (1-i\cot(\omega t))}\right)$$

---
We have
$$\ket{\psi_R}=\hat{U}\ket{\psi_T}$$
which is some [[3QC. Unitary Operator|unitary operator.]]