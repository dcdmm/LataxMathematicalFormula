vscode环境:一个公式环境中只能有一个公式编号

$$
f_m(x) = f_{m-1}(x) + \beta_m b(x;\gamma_m) % 不会自动编号
$$


$$
\begin{equation}
f_m(x) = f_{m-1}(x) + \beta_m b(x;\gamma_m)  % equation环境:自动编号
\end{equation}
$$


$$
% gather环境:自动编号
% gathered环境:不自动编号
% 手动编号:环境中最后一行的位置
\begin{gather}
a + b = b + a + c + d \\
a + b = b + a + c + d \\
a + b = b + a + c + d \\
a + b = b + a + c + d \\
a + b = b + a + c + d 
\end{gather}
$$


$$
% align环境:自动编号
% aligned环境:不自动编号
% 手动编号:环境中最后一行的位置
\begin{align}
x &= t + \cos t + 1\\
x &= t + \cos t + 1 \\
x &= t + \cos t + 1 \\
x &= t + \cos t + 1 \\
x &= t + \cos t + 1 \\
x &= t + \cos t + 1 \\
\end{align}
\tag{1.2}
$$


$$
% array环境:不自动编号
% 手动编号:环境中最后一行的位置
\begin{array}{rcr}
f(x,y,z) & = & x + y + z  \\
f(x,y,z) & = & x + y + z   \\
f(x,y,z) & = & x + y + z  \\
f(x,y,z) & = & x + y + z  \\
\end{array}
% \tag{1.3}
$$


$$
% matrix环境:不自动编号
% 手动编号:环境内最后一行位置
\begin{matrix}
a_{11} & a_{12} & a_{13} \\
0      & a_{22} & a_{23} \\
0	   & 0      & a_{33}   
\end{matrix}
\tag{1.4}
$$