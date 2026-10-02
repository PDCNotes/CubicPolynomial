# Cubic Polynomial
Properties of cubic polynomials.

## General Cubic Polynomial
$$\huge \begin{aligned}
  y(x) &=a{x}^{3}+b{x}^{2}+c{x}+d \\
 y'(x) &=3a{x}^{2}+2b{x}+c \\
y''(x) &=6a{x}+2b \\
\end{aligned} $$

Map $y(x)\to Y(t) $

$$\huge \begin{aligned}
     B &=\dfrac{b}{a} \\
     C &=\dfrac{c}{a} \\
     D &=\dfrac{d}{a} \\
     P &={B}^{2}-3C \\
     Q &=B(2{B}^{2}-9C)+27D=B(2P-3C)+27D \\
     \\
     y &=aY \\
     x &=t-\dfrac{B}{3} \\
     \\
  Y(t) &=\dfrac{27{t}^{3}-9Pt+Q}{27} \\
 Y'(t) &=\dfrac{9{t}^{2}-P}{3} \\
Y''(t) &=6{t} \\
\end{aligned} $$



$\huge y(x)=a{x}^{3}+b{x}^{2}+c{x}+d $

$\huge y'(x)=3a{x}^{2}+2b{x}+c $

$\huge y''(x)=6a{x}+2b $

$\huge B=\dfrac{b}{a} $

$\huge C=\dfrac{c}{a} $

$\huge D=\dfrac{d}{a} $

$\huge P={B}^{2}-3C $

$\huge Q=B(2{B}^{2}-9C)+27D=B(2P-3C)+27D $





### Map $y(x)\to Y(t) $

$\huge Y=\dfrac{y}{a} \to y=aY $

$\huge x=t-\dfrac{B}{3} $


$\huge Y(t)=\dfrac{27{t}^{3}-9Pt+Q}{27} $

$\huge Y'(t)=\dfrac{9{t}^{2}-P}{3} $

$\huge Y''(t)=6{t} $

### Inflection Point

$\huge Y''(t)=6{t}=0 @ t=0 \therefore x=-\dfrac{B}{3} $

$\huge Y'(0)=-\dfrac{P}{3} \therefore y'=-\dfrac{a}{3}P $

# Testing

$$\huge \begin{aligned}
    x_1 &= 1 \\
    x_2 &= 2 \\
    x_3 &= 3
\end{aligned} $$

$\huge Y={x}^{3}+B{x}^{2}+C{x}+D $


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


