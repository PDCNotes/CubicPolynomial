# Cubic Polynomial
Properties of cubic polynomials.



$$y=ax^3+bx^2+cx+d$$


```math
\huge y=a \cdot x^3 + b \cdot x^2 + c \cdot x + d
```

$\huge y=a \cdot x^3 + b \cdot x^2 + c \cdot x + d$

$\huge y'=3a \cdot x^2 + 2b \cdot x + c$

$\huge y''=6a \cdot x + 2b$

$\huge y''=0 @ x=-\frac{b}{3a}$

$\huge y'=0 @ x=-\frac{b}{3a} \pm \frac{\sqrt{b^2-3ac}}{3a}$

$\huge y'=0 @ x=-\frac{b}{3a} \pm \sqrt{\left(\frac{b}{3a}\right)^2-\frac{c}{3a}}$

Location x where $\huge   y' = -y' @ y''=0 @ x=-\frac{b}{3a}$

$\huge y'=0 @ x=-\frac{b}{3a} \pm \sqrt{2\left[\left(\frac{b}{3a}\right)^2-\frac{c}{3a}\right]}$

## Roots of Cubic Polynomial

$\huge B=\frac{-2b}{a}$

$\huge C=\frac{6c}{a}$

$\huge D=\frac{-108d}{a}$

$\huge P=B^2-2C$

$\huge Q=B(P-C)+D$

$\huge V=C^2(3P-2C)-D(2Q-D)$

If $\huge V >= 0$, three real value roots.

If $\huge Q^2 = V = 0$ then $\huge T = 0$

$\huge T=\frac{ATAN2(Q,\sqrt{V})}{3}$

$\huge R=\sqrt{P}$

$\huge X=R cos(T)$

$\huge Y= \sqrt{3} R sin(T)$

$$\huge x=
\left[
\begin{array}{l}
  \frac{B+X+X}{6} \\
  \frac{B-X+Y}{6} \\
  \frac{B-X-Y}{6}
\end{array}
\right] $$

$$ \huge x=\begin{bmatrix}  \frac{B+X+X}{6} \\  \frac{B-X+Y}{6} \\  \frac{B-X-Y}{6} \end{bmatrix} $$

Elseif $\huge V < 0$, one real value root.

$\huge x=\frac{B+\sqrt[3]{Q+\sqrt{-V}}+\sqrt[3]{Q-\sqrt{-V}}}{6}$

