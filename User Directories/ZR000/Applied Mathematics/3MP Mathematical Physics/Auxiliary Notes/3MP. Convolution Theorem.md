Index: [[Index for 3MP Mathematical Physics]]

# The Convolution Theorem
 Suppose
 $$f(x)=\int F(k)e^{-ikx}dk$$
 $$g(x)=\int G(k)e^{-ikx}dk$$
 $$H(k)=F(k)G(k)$$
 $$h(x)=\int H(k)e^{-ikx}dk$$

What is the dependency of $h$ on $f,g$? Well,
$$h(x)=\int F(k)G(k)e^{-ikx}dk$$
$$h(x)=\int \left[\frac{1}{2\pi}\int f(x')e^{ikx'}dx'\right]G(k)e^{-ikx}dk$$
$$h(x)=\frac{1}{2\pi}\int f(x')\left[\int G(k)e^{-ik(x-x')}dk\right]dx'$$
$$h(x)=\frac{1}{2\pi}\int f(x')g(x-x')dx'$$

We call this quantity, 
$$(f*g)(x)=\frac{1}{2\pi}\int f(x')g(x-x')dx'$$
the convolution of $f$ and $g$.

Hence, the function $h$ whose fourier integral $H$ is the product of the fourier integrals $F,G$ of two other functions $f,g$ is the convolution $f*g$ of those functions; $h=f*g$.

Index: [[Index for 3MP Mathematical Physics]]