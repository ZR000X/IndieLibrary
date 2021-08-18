Index: [[Index for 3MP Mathematical Physics]]

Here, we want to compute the integral
$$I=\int_{-\infty}^\infty e^{-\alpha^2 k^2 t}e^{-ikx}dk,~~~~\alpha^2>0$$

The technique we'll use starts with completing there square of the exponential quantity with respect to the integration variable $k$:
$$-\alpha^2 k^2 t-ikx=-\left(\underbrace{\alpha t^{1/2}k+\frac{ix}{2\alpha t^{1/2}}}_{k'}\right)^2-\frac{x^2}{4\alpha^2 t}$$

As indicated, we let the bracketed variable be $k'$, 
$$k'=\alpha t^{1/2}k+\frac{ix}{2\alpha t^{1/2}}$$
which is only a linear change of $k$. This change of variables will provide a remarkable simplification, as $k'$ has the same limits as $k$, since they are the infinities, and the differential $$dk'=\alpha t^{1/2}dk$$

We have $$I=\frac{1}{\alpha t^{1/2}}\int_{-\infty}^\infty \exp\left(-k'^2-\frac{x^2}{4\alpha^2 t}\right)dk'$$
$$I=\frac{\exp\left(-\frac{x^2}{4\alpha^2 t}\right)}{\alpha t^{1/2}}\underbrace{\int_{-\infty}^\infty e^{-k'^2}dk'}_{\sqrt{\pi}}$$
where the integral known as the Gaussian integral is worked out [[3MP. Calculation of the Gaussian Integral|here]] and is $\sqrt{\pi}$.

Hence, $$I=\sqrt{\frac{\pi}{\alpha^2 t}}\exp\left(-\frac{x^2}{4\alpha^2 t}\right)$$


Index: [[Index for 3MP Mathematical Physics]]