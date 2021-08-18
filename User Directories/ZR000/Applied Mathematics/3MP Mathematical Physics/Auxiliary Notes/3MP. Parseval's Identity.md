Index: [[Index for 3MP Mathematical Physics]]

Recall the [[3MP. Convolution Theorem|Convolution theorem]]: the function $h$ whose fourier integral $H$ is the product of the fourier integrals $F,G$ of two other functions $f,g$ is the convolution $f*g$ of those functions; $h=f*g$, where $$(f*g)(x)=\frac{1}{2\pi}\int f(x')g(x-x')dx'=\int F(k)G(k)e^{-ikx}dk$$
where $\mathcal{F}[f(x)]=F(k)$ and $\mathcal{F}[g(x)]=G(k)$, if $\mathcal{F}[h]$ denotes the Fourier integral of $h$. 

To obtain Parseval's identity, we observe
$$I=(f*g)(0)=\frac{1}{2\pi}\int f(x')g(-x')dx'=\int F(k)G(k)dk$$
and in the special case of $g(x)=f^*(-x)$,
$$I=\frac{1}{2\pi}\int |f(x')|^2dx'$$

We also know that, for arbitrary function $y(x)$,
$$\mathcal{F}[y(x)]=Y(k)$$
$$\Rightarrow y(x)=\int Y(k)e^{-ikx}dk$$
$$\Rightarrow y^*(x)=\int Y^*(k)e^{ikx}dk$$
$$\Rightarrow y^*(-x)=\int Y^*(k)e^{-ikx}dk$$
$$\therefore \mathcal{F}[y^*(-x)]=\mathcal{F}[y(x)]^*$$
and its variations.

Hence, we can easily find
$$\int |f(x)|^2dx=2\pi\int |F(k)|^2dk$$
