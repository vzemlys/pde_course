$$
y_i = X_i\beta + u_i\\

\hat\beta=argmin_{\beta}\sum_{i=1}^n(y_i-X_i\beta)'(y_i-X_i\beta) = argmin_{\beta}\sum_{i=1}^n\|y_i-X_i\beta\|^2\\
\|z\| = \sqrt{\sum_{i=1}^nz_i^2}\\
\|z\|_p=(\sum_{i=1}^n|z_i|^p)^{1/p} 
$$

$$
X_i\sim p_\theta\\
X_i\sim F_\theta\\

\hat\theta_{LLF} = argmax_\theta\sum_{i=1}^n\log p_\theta(X_i)
$$

$$
p_\beta (y, X) = \frac{1}{\sigma\sqrt{2\pi}} \exp(\frac{-(y-X\beta)^2}{2\sigma^2})\\
\log p_\beta (y, X) = -log\sigma-\frac{1}{2}\log(2\pi)-
\frac{(y-X\beta)^2}{2\sigma^2}$$

$$
\frac{1}{\sqrt{N}}\sum_{i=1}^nY_i \to N(0, Var Y_i)
$$

$$
AVar(\hat\beta) = \sigma^2(X'X)^{-1}/N
$$

$$
E(X_i'u_iu_i'X_i)= \sigma^2E(X_i'X_i)\\
E(u_iu_i')=\sigma^2I
$$

$$
cov(X^2,X) = E(X^2-EX)(X-EX)= EX^3 -(EX)^2\\
EX^3=0, EX=0
$$

$$
\Omega=Eu_iu_i=E\begin{pmatrix}u_{i1}\\\vdots\\ u_{iT}\end{pmatrix}(u_{i1},...,u_{iT})=\begin{pmatrix}Var(u_{i1}) & ... & cov(u_{i1},u_{iT})\\
\dots & \dots & \dots\\
cov(u_{i1},u_{iT}) & ... & Var(u_{iT})
\end{pmatrix}
$$

$$
R\beta=R\begin{pmatrix}\beta_{1}\\\vdots\\ \beta_{K}\end{pmatrix}=\beta_1\\
R=\begin{pmatrix}1, 0\dots 0\end{pmatrix}
r=0
$$

$$
x'\Omega x=\sum_{i=1}^K\sum_{j=1}^K\sigma_{ij}x_ix_j>0, \forall x\neq 0\\
\Omega >0\\
\Omega_1,\Omega_2, \Omega_1-\Omega_2>0 \Rightarrow \Omega_1>\Omega_2 
$$
