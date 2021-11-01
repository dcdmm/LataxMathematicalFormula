typora/notebook:所有公式环境均不会自动编号

$$
% gather环境:可以自定义多个公式编号
% gathered环境:只能有一个公式编号且在环境中的最后一行
\begin{gather}
a + b = b + a + c + d \tag{1} \\
a + b = b + a + c + d \tag{2}\\
a + b = b + a + c + d \tag{3}\\
a + b = b + a + c + d \tag{4}\\
a + b = b + a + c + d \tag{5}
\end{gather}
$$


$$
% align环境:可以自定义多个公式编号
% aligned环境:只能有一个公式编号且在环境中的最后一行
\begin{align}
x &= t + \cos t + 1 \tag{1.1} \\
x &= t + \cos t + 1 \tag{1.2} \\
x &= t + \cos t + 1 \tag{1.3}\\
x &= t + \cos t + 1 \tag{1.4}\\
x &= t + \cos t + 1 \tag{1.5} \\
x &= t + \cos t + 1 \tag{1.6}\\
\end{align}
$$


$$
% array环境:只能有一个公式编号且在环境中的最后一行
\begin{array}{rcr}
f(x,y,z) & = & x + y + z \tag{13.3} \\
f(x,y,z) & = & x + y + z  \\
f(x,y,z) & = & x + y + z  \\
f(x,y,z) & = & x + y + z  \\
\end{array}
$$


$$
% matrix环境:只能有一个公式编号且在环境中的最后一行
\begin{matrix}
a_{11} & a_{12} & a_{13}  \\
0      & a_{22} & a_{23} \\
0	   & 0      & a_{33}   
\end{matrix}
\tag{1.4}
$$

