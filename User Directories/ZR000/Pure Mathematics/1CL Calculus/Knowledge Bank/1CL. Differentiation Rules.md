# The Power Rule
$$f(x)=x^n~~\Rightarrow~~f'(x)=nx^{n-1}$$

# The Product Rule
$$h(x)=f(x)g(x)~~\Rightarrow~~h'(x)=f'(x)g(x)+f(x)g'(x)$$

**PROOF:** Note that $$dF(x)=F(x+dx)-F(x)$$ and $$dF(x)=F'(x)dx$$ for all functions $F$, by definition.

Thus 
$$dh(x)=f(x+dx)g(x+dx)-f(x)g(x)$$ 
$$\Rightarrow~~dh(x)=[df(x)+f(x)][dg(x)+g(x)]-f(x)g(x)$$
$$\Rightarrow~~dh=\underbrace{dfdg}_0+gdf+fdg+fg-fg$$
$$\therefore \frac{dh(x)}{dx}=\frac{df(x)}{dx}+f(x)\frac{dg(x)}{dx}$$
$$\Rightarrow~~h'(x)=f'(x)g(x)+f(x)g'(x)$$

**PROOF BY LIMITS**
... follows simply from the above

# Quotient Rule
$$h(x)=\frac{f(x)}{g(x)}~~\Rightarrow~~h'(x)=\frac{f'(x)g(x)-g'(x)f(x)}{g(x)^2}$$

**PROOF:** $$\Delta h(x)=\frac{f(x+\Delta x)}{g(x+\Delta x)}-\frac{f(x)}{g(x)}$$
$$\Rightarrow~~\Delta h(x)=\frac{f(x)+\Delta f(x)}{g(x)+\Delta g(x)}-\frac{f(x)}{g(x)}$$
$$\Rightarrow~~\Delta h=\frac{\left[f+\Delta f\right]g-f\left[g+\Delta g\right]}{\left[g+\Delta g\right]g}$$
$$\Rightarrow~~\Delta h=\frac{fg+g\Delta f-fg-f\Delta g}{g\Delta g+g^2}$$
$$\Rightarrow~~\frac{\Delta h}{\Delta x}=\frac{g\frac{\Delta f}{\Delta x}-f\frac{\Delta g}{\Delta x}}{g\Delta g+g^2}$$

Taking the limit as $\Delta x\to 0$, we have
$$h'(x)=\lim_{\Delta x\to 0}\frac{g\frac{\Delta f}{\Delta x}-f\frac{\Delta g}{\Delta x}}{g\Delta g+g^2}$$

Using limit laws, particularly the sum, product, and quotient laws, we have, letting
$$L\equiv\lim_{\Delta x\to 0},$$
that
$$h'=\frac{gL\frac{\Delta f}{\Delta x}-fL\frac{\Delta g}{\Delta x}}{gL\Delta g+g^2}$$

Using what we know about limits, 
$$h'=\frac{gf'-fg'}{g\cdot0+g^2}$$
$$\therefore h'(x)=\frac{f'(x)g(x)-g'(x)f(x)}{g(x)^2}$$

QED.
