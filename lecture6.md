$$
y_t = x_t\beta+c+u_t\\
\Delta y_t = \Delta x_t\beta + \Delta u_t\\
\Delta y_t = \Delta x_t\gamma + v_t\\
Eu_t=0, Var(u_t)=\sigma^2, Eu_tu_{t-s}=0, \text{ for all } s\\
\nu_t = u_t-u_{t-1} 
$$

$$
E(u_{it}|y_{i,t-1},...,y_{i,1}, c_i)=0\\
E(y_{i,t-1}u_{it})=EE(y_{i,t-1}u_{it}|y_{i,t-1},...,y_{i,1},c_i)=Ey_{i,t-1}E(u_{it}|y_{i,t-1},...,y_{i,1},c_i)=0
$$

$$
y_{t}=y_{t-1}\theta+u_t\\
y_{t}= y_0\theta^{t}
+\sum_{s=0}^t\theta^su_{t-s}\\
y_{t}= y_{t-1}\theta+u_t=\\
 u_t + (y_{t-2}\theta+u_{t-1})\theta=\\
u_t+u_{t-1}\theta+\theta^2 y_{t-2}=\\
u_t+u_{t-1}\theta+\theta^2(\theta y_{t-3}+u_{t-2})=\\
u_t+u_{t-1}\theta+\theta^2u_{t-2}+\theta^3y_{t-3}\\
E(y_tu_t)=E(y_0+\sum_{s=0}^t\theta^su_{t-s})u_t=Ey_0u_t+\sum_{s=0}^t\theta^sEu_{t-s}u_t=Eu_t^2\\
E(y_tu_t)=E(\theta y_{t-1}u_t+u_t^2)
$$

$$
\hat{v}_{it} =y_{it}-x_{it}\hat\beta\\
Ev_{it}^2=\sigma_c^2+\sigma_u^2=\sigma_v^2\\
\hat\sigma_v^2=\frac{1}{NT-K}\sum_{i=1}^N\sum_{t=1}^T\hat v_{it}^2\\
E\hat\sigma_v^2=\sigma_v^2\\
\frac{NT-K}{NT}\to 0, \text{ as } N\to\infty

$$

$$
y_{i,t}=y_{i,t-1}\beta+c_i+u_{i,t}\\
E(y_{i,t-1}c_i)=E(y_{i,t-2}\beta+c_i+u_{i,t-1})c_i=\beta E(y_{i,t-2}c_i)+Ec_i^2+E(u_{i,t-1},c_i)
$$
