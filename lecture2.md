$$
f(x) = f(a) + f'(a)(x-a) + o(x-a), x\to a
$$

$$
f(x) = f(a) + f'(a)(x-a) + f''(a)(x-a)^2+o((x-a)^2), x\to a
$$

$$
f(x) = f(a) + f'(a)(x-a) + f''(a)(x-a)^2+...+f^{(n)}(a)(x-a)^n+ o((x-a)^n) , x\to a
$$

$$
f(x_1, x_2, ..., x_d) = f(a) + \sum_{i=1}^d\frac{\partial f}{\partial x_i}(a)(x_i-a_i)+(\|x-a\|),  x\to a
$$

\$\$ f(x_1, x_2, ..., x_d) = f(a) + \sum*{j=1}\^n*\sum{i_1,...,i_j=1}^d^\frac{\partial^n f}{\partial x_{i_1}...\partial x_{i_j}}(a)(x\_{i_1}-a\_{i_1})\cdot\cdot\cdot(x\_{i_j}-a\_{i_j})+(\|x-a\|n), x\to a

\$\$

$$
f(a) + \sum_{i=1}^d\frac{\partial f}{\partial x_i}(a)(x_i-a_i) =  f(a)-\sum_{i=1}^d\frac{\partial f}{\partial x_i}(a)a_i+\sum_{i=1}^d\frac{\partial f}{\partial x_i}(a)x_i
$$

$$
\beta_0=f(a)-\sum_{i=1}^d\frac{\partial f}{\partial x_i}(a)a_i\\
\beta_i=\frac{\partial f}{\partial x_i}(a)\\
y = f(x_1,...,x_d)\\
y = \beta_0+\sum_{i=1}^d\beta_ix_i + u
$$

\$\$ \log(wage) = \beta\_0+\beta\_1educ+\beta\_2exper+\beta\_3married + \beta\_4 gender +u\\ \log(wage) = \beta\_0+\beta\_1educ+\beta\_2exper+\beta\_3married + \beta\_4 gender + \beta\_5 gender\times educ + u\\ \log(wage) = \beta\_0+\beta\_4 + (\beta\_1+\beta\_5)educ+\beta\_2exper+\beta\_3married + u, gender = 1\\ \log(wage) = \beta\_0 +\beta\_1educ+\beta\_2exper+\beta\_3married + u, gender = 0

\$\$

$$
\beta_1 = \frac{\partial \log (output)}{\partial \log (labor)} = \frac{\partial(output)}{\partial (labour)}\frac{labour}{output}
$$

$$
f(K,L) = K^\alpha L^{\beta}\\
log(f(K,L)) = \alpha\log K+\beta\log L
$$

$$
(y_i, x_i, u_i)\\
y_i = x_i\beta + u_i\\
E(y_i|x_i) = x_i\beta\\
E(u_i|x_i) = 0\\
E(u_i)=0
$$

$$
\hat{u_i} = y_i-x_i\hat\beta_{OLS}\\
\sum_{i=1}^n\hat{u_i}= 0
$$

\$\$ y\_{it}=x\_{it}\beta+u\_{it}, i=1,..,N, t=1,...,T\\

y\_{i} = x\_{i}\beta+u_i \$\$

\$\$ y_i = x_i\beta+u_i,\\ y_i'=(y\_{i1},...,y\_{iT}), x_i=

```{=tex}
\begin{pmatrix}x_{i11} & ... &x_{iK1}\\
... & ... & ...\\
x_{i1T} & ... & x_{iKT}\end{pmatrix}
```
, u_i' = (u\_{i1},...,u\_{iT})

\$\$
