Welcome on my Github profile !
<a name="ex02"></a>
$$
\begine{equation}
  A = \sum_i^N x_i
\end{equation}
$$

$$
\begin{equation}
    y_j =
    \begin{cases}
      R_j & \text{if episode terminates at step  } j+1\\
      R_j + \gamma \max_{a'}\hat{Q}(s_{j+1},a') & \text{otherwise}\\
    \end{cases}       
\end{equation}
$$
