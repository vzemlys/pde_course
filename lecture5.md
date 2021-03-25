$$
H_0: \beta = \beta_0\\
H_0: \beta = 0\\
t = \frac{\hat\beta - \beta_0}{SD(\hat \beta)}\\
t_1 = \frac{\tilde\beta - \beta_0}{SD(\tilde \beta)}\\
SD(\hat\beta) > SD(\tilde\beta)\\
t_1 > t
$$

$$
E(y_t|x_t,y_{t-1},x_{t-1},...,y_1, x_1) = E(y_t|x_t)\\
y_t = x_t\beta+u_t\\
y_{t} = x_{1t}\beta_1+x_{1,t-1}\beta_2 + u_t\\
x_t = (x_{1t},x_{1,t-1})\\
x_{t-1} = (x_{1,t-1},x_{1,t-2})\\
E(y_t|x_t, x_{t-1}) = E(y_t|x_t)
$$

$$
y_t = \beta_0+x_{1,t}\beta_1+x_{2,t}\beta_2+u_t\\
y_t = \beta_0+x_{1,t}\beta_1+\tilde{u}_t \\
\tilde{u}_t= x_{2,t}\beta_2+u_t\\
Ex_{1,t}u_t=0,Ex_{2,t}u_t=0\\
Ex_{1,t}\tilde{u}_t = \beta_2Ex_{1t}x_{2,t}}+Ex_{1,t}u_t
$$

$$
y_{it} = x_{it}\beta+ c_i + u_{it}
$$
