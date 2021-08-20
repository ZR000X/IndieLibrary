Index: [[Index for 3MP Mathematical Physics]]

See: [Wikipedia Article](https://en.wikipedia.org/wiki/Gaussian_integral)


THE BELOW IS WRONG

We wish to calculate the integral
$$I=\int_{-\infty}^{\infty}e^{-x^2}dx=2\int_{0}^{\infty}e^{-x^2}dx$$

Observe that
$$I^2=4\int_{0}^{\infty}e^{-x^2}dx\int_{0}^{\infty}e^{-y^2}dy$$

Noting that, transforming to [polar coordinates](https://en.wikipedia.org/wiki/Polar_coordinate_system), we have
$$I^2=4\int_{0}^{\pi}\int_{0}^{\infty}e^{-r^2}rdrd\theta$$

Separating,
$$I^2=4\underbrace{\int_{0}^{\pi}d\theta}_{\pi}\int_0^{\infty}re^{-r^2}dr$$

Letting $u=r^2$, $du=2r dr$,
$$I^2=2\pi\underbrace{\int_{0}^{\infty}e^{-u}du}_{-(e^{-\infty}-e^0)=1}$$

Computing,
$$I^2=\pi e^{-u}|_{-\infty}^{\infty}$$