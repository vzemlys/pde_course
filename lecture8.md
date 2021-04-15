$$
\ddot{u}_{it} = u_{it}-\bar{u}_{i}\\
\bar{u}_i = \frac{1}{T}\sum_{t=1}^Tu_{it}\\
\bar{u}_i = \frac{1}{2}(u_{i1}+u_{i2})\\
\ddot{u}_{i1} = u_{i1}-\frac{1}{2}(u_{i1}+u_{i2})= \frac{1}{2}(u_{i1}-u_{i2})=-\frac{1}{2}\Delta u_{i2}\\
\ddot{u}_{i2} = u_{i2}-\frac{1}{2}(u_{i1}+u_{i2})=\frac{1}{2}(u_{i2}-u_{i1})=\frac{1}{2}\Delta u_{i2}
$$

$$
\Delta u_{it} = e_{it}\\
u_{it}= u_{i,t-1}+e_{it} = \sum_{s=1}^te_{is}
$$

\$\$ \hat\beta*{FE}-*\beta=(\sum{i=1}^N^\sum*{t=1}^T^*\ddot x\_{it}'\ddot x\_{it}){-1}(\sum{i=1}N\sum*{t=1}\^T*\ddot x{it}'\ddot u\_{it})\\ \hat\beta*{FD}-*\beta=(\sum{i=1}^N^\sum*{t=1}^T^*\Delta x\_{it}'\Delta x\_{it}){-1}(\sum{i=1}N\sum*{t=1}\^T*\Delta x{it}'\Delta u\_{it})\\

\$\$

\$\$ \lambda = 1 - \frac{\sigma_u^2}{\sigma_u^2+T\sigma_c^2}\\

y\_{it} - \lambda\bar{y}*{it} = y*{it}, \text{ if } \sigma*c\^2=0\\ y*{it} - \lambda\bar{y}*{it} =y*{it}-\bar{y}\_{it} \text{ if } \lambda = 1. \$\$

$$
\hat\theta\to N(0, \Sigma)\\
\theta'\Sigma^{-1}\theta\sim \chi^2_d\\
\hat{\theta}_{RE}-\hat{\theta}_{FE}\to N(0, \Omega)
$$

$$
EX_i'u_i=0\\
EX_i'(y-X_i\beta)=0\\
EX_i'y = EX_i'X_i\beta\\
\hat\beta = (EX_i'X_i)^{-1}EX_i'y_i
$$

$$
EZ_i'(y_i-X_i\beta) =0 \\
EZ_i'y_i = EZ_i'X_i\beta\\
\beta = (EZ_i'X_i)^{-1}EZ_i'y_i, \text{ when  } L = K, \text{ where } Z_i \text{ is } G\times L, \text{ and } X_i \text{ is } G\times K  
$$

$$
\min \sum_{i=1}^Nx_i(\beta)^2
$$
