$$
y_{it} = x_{it}\beta+u_{it}\\
\hat\beta=(\sum_{i=1}^N\sum_{t=1}^Tx_{it}'x_{it})(\sum_{i=1}^N\sum_{t=1}^Tx_{it}'y_{it})\\
\sigma^2=Eu_{it}^2\\
\hat\sigma^2=\frac{1}{NT}\sum_{i=1}^N\sum_{t=1}^T\hat{u}_{it}\\
\hat{u}_{it} = y_{it}-x_{it}\hat\beta\\
\ddot u_{it} = u_{it} - \frac{1}{T}\sum_{t=1}^Tu_{it}\\
E\ddot u_{it}^2=E(u_{it} - \frac{1}{T}\sum_{t=1}^Tu_{it})^2 = Eu_{it}^2-2\frac{1}{T}\sum_{s=1}^TEu_{it}u_{is} + \frac{1}{T^2}E(\sum_{t=1}^Tu_{it})^2=\\
Eu_{it}^2-\frac{2}{T}Eu_{it}^2+\frac{1}{T^2}\sum_{s=1}^T\sum_{t=1}^TEu_{it}u_{is} = 
Eu_{it}^2-\frac{2}{T}Eu_{it}^2+\frac{1}{T^2}TEu_{it}^2= (1-\frac{1}{T})Eu_{it}^2= \frac{T-1}{T}Eu_{it}^2
$$

$$
\hat{v}_{it}=y_{it}-x_{it}\hat\beta\\
\hat\alpha = \frac{1}{NT}\sum_{i=1}^N\sum_{t=1}^T\hat{v}_{it}\\
\hat{c_i}=\frac{1}{T}\sum_{t=1}^T\hat{v}_{it}-\hat\alpha\\
\hat{u}_{it} = y_{it}-\hat\alpha -x_{it}\hat\beta \\
\sum_{i=1}^N\sum_{t=1}^T\hat{u}_{it}=0\\
\sum_{i=1}^N\hat c_i=0
$$

\$\$ y_t = x_t\beta+u_t\\ u_t = \rho u\_{t-1} + v\_{t}

\$\$

$$
v_{it}=c_i+u_{it}\\
\bar{v}_i=\frac{1}{T}\sum_{t=1}^Tv_{it}=c_i+\frac{1}{T}\sum_{i=1}^Tu_{it}
$$
