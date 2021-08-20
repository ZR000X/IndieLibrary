I did some math.

Define the graph of a circle centred at the origin by the function
$$f_1(x)=\sqrt{r^2-x^2}$$
for some radius $r$.

Define some line by the function
$$f_2(x)=mx$$
which goes through the origin and intersects with the circle $f_1$ at the point $(x_0,mx_0)$ (as well as another point, but we needn't the other).

Now consider another line, which we call a tangent to the circle, defined by the function
$$f_3(x)=m_1x+c$$
and also goes through the point $(x_0,mx_0)$.

We want to prove that $f_2$ is perpendicular to $f_3$, which is equivalent to ([[Proving that Perpendicular Lines have Gradient Product -1|why?]]) $$m=-\frac{1}{m_1}$$

Firstly, we know that
$$f_3(x_0)=m_1x+c=mx_0$$
$$\therefore c=(m-m_1)x_0$$
$$\therefore f_3(x)=m_1x+(m-m_1)x_0$$

Now, the plan is to equate the functions of the circle $f_1$ and the tangent $f_3$ and solve for the possible values of $x$. The defining feature of the tangent is that it only intersects the circle at one point, so we will force our solution for the intersections $x$ to have only one distinct value. Doing so should constrain our system sufficiently.

Perform the equation,
$$m_1x+(m-m_1)x_0=\sqrt{r^2-x^2}$$

We can extract a formula for $r$ by again substituting the point $(x_0,mx_0)$,
$$\sqrt{r^2-x_0^2}=mx_0$$
$$\therefore r^2=(m^2+1)x_0^2$$
$$\therefore m_1x+(m-m_1)x_0=\sqrt{(m^2+1)x_0-x^2}$$

Squaring both sides,
$$m_1^2x^2+2m_1(m-m_1)x_0x+(m-m_1)^2x_0^2=(m^2+1)x_0^2-x^2$$
$$(m_1^2+1)x^2+2m_1(m-m_1)x_0x+[m^2-2mm_1+m_1^2-m^2-1]x_0^2=0$$
$$\underbrace{(m_1^2+1)}_ax^2+\underbrace{2m_1(m-m_1)x_0}_bx+\underbrace{[m_1^2-2mm_1-1]x_0^2}_c=0$$

Using the quadratic equation, we would get solutions for $x$, but we only want the determinant to be zero, which would force only one unique solution for $x$,
$$\Delta=b^2-4ac=0$$
$$\Rightarrow (2m_1(m-m_1)x_0)^2-4(m_1^2+1)(m_1^2-2mm_1-1)x_0^2=0$$
$$\Rightarrow m_1^2(m^2-2mm_1+m_1^2)-(m_1^2+1)(m_1^2-2mm_1-1)=0$$
$$\Rightarrow m^2m_1^2-2mm_1^3+m_1^4-m_1^4+2mm_1^3+m_1^2-m_1^2+2mm_1+1=0$$

After much convenient cancellation,
$$m^2m_1^2+2mm_1+1=0$$

Solving for $m$ using the quadratic equation, we find
$$m=-\frac{1}{m_1}$$

QED.
