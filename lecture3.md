$$
y_1 = \mathbf{x_1}\mathbf{\beta_1} + u_1\\
y_G = \mathbf{x_G}\mathbf{\beta_G} + u_G
$$

$$
x_g = x, g=1,...,G
$$

$$
y_1 = \mathbf{x}\mathbf{\beta_1} + u_1\\
y_G = \mathbf{x}\mathbf{\beta_G} + u_G
$$

$$
y_1 = x\beta + u_1\\
y_G = x\beta + u_G
$$

$$
i=1,...,N. y_{11},...,y_{1N},...,y_{G1},...,y_{GN}\\
x_1 = (x_{11},...,x_{1K}),...,x_N=(x_{N1},...,x_{NK})
$$

$$
i=1,...,N. y_{11},...,y_{1N},...,y_{G1},...,y_{GN}\\
x_{11} = (x_{111},...,x_{11K}),...,x_{1N}=(x_{1N1},...,x_{1NK})\\
x_{G1} = (x_{G11},...,x_{G1K}),...,x_{GN}=(x_{GN1},...,x_{GNK})\\
$$

$$
\beta_g=\beta?, g=1,...,G
$$

$$
y_i=X_i\beta+u_i
$$

$$

$$

$$
\begin{pmatrix}y_{i1}\\\vdots\\y_{iT}\end{pmatrix} = \begin{pmatrix}x_{i11} &... &x_{i1K}\\
\dots&\dots&\dots\\
x_{iT1} & \dots &x_{iTK}\\\end{pmatrix}\begin{pmatrix}\beta_1\\\vdots\\\beta_K\end{pmatrix}+\begin{pmatrix}u_{i1}\\\vdots\\ u_{iT}\end{pmatrix}
$$

$$
Y=X\beta+u\\\
\hat\beta=(X'X)^{-1}X'Y\\
Y=\begin{pmatrix}y_1\\\vdots\\y_N\end{pmatrix}\\
X=\begin{pmatrix}x_{11} & \dots & x_{1K}\\
\dots &\dots&\dots\\
x_{N1} & \dots & x_{NK}
\end{pmatrix} = \begin{pmatrix}x_1'\\\dots\\x_N'\end{pmatrix}\\
X'=\begin{pmatrix}
x_{11} & \dots & x_{N1}\\
\dots & \dots & \dots\\
x_{1K} & \dots & x_{NK}
\end{pmatrix}\\
X'X = \begin{pmatrix}
\sum_{i=1}^nx_{i1}^2 & \dots & \sum_{i=1}^nx_{i1}x_{iK}\\
\dots&\dots&\dots\\
\sum_{i=1}^nx_{iK}x_{i1}^2 & \dots & \sum_{i=1}^nx_{iK}^2\\ 
\end{pmatrix} = \sum_{i=1}^n\begin{pmatrix}
x_{i1}^2 & \dots & x_{i1}x_{iK}\\
\dots&\dots&\dots\\
x_{iK}x_{i1}^2 & \dots & x_{iK}^2\\ 
\end{pmatrix} = \sum_{i=1}^n\begin{pmatrix}x_{i1}\\\vdots\\x_{iK}\end{pmatrix}\begin{pmatrix}x_{i1} \dots x_{iK}\end{pmatrix}
$$

$$
\hat\beta=(\sum_{i=1}^n x_{i}x_i')^{-1}\sum_{i=1}^nx_iy_i
$$

$$
X
$$
