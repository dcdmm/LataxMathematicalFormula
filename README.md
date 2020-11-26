## 关于显示
* GitHub显示不完全,若要完全查看请下载到本地!

## 关于数学公式符号
1. 单行公式

   1. Typora:\$.*\$或\$\$.\*\$\$
   2. Pycharm或Jupyter Notebook:\$.*\$

2. 多行公式

   1. Typora(自动居中对齐):
      ```markdown
      $$
      .*
      $$
      ```

   2. Pycharm或Jupyter Notebook:\$\$.\*\$\$

      1. Jupyter Notebook多行公式自动居中对齐

      2. Pycharm多行公式(默认左对齐)若要居中对齐,请使用下面的方式  

         ```markdown
         <center>
         
         $$ x = t + \cos t + 1 $$
         </center>
         ```

3. 公式环境

   1. Typora(自动居中对齐):

      ```markdown
      $$
      \begin{align}
      x &= t + \cos t + 1\\
      y &= 2 \sin 5
      \end{align}
      $$
      ```

   2.  Jupyter Notebook公式环境公式自动居中对齐

      ```markdown
      \begin{align}
      x &= t + \cos t + 1\\
      y &= 2 \sin 5
      \end{align}
      ```

   3. Pycharm公式环境(默认左对齐)若要居中对齐,请参考以下方式
	```markdown
	<center>

	\begin{align}
	x &= t + \cos t + 1\\
	y &= 2 \sin 5
	\end{align}
	</center>
	```
	```markdown
	<center>

	\begin{equation} %必须用公式环境包含
	(p_1 + ... + p_n)^m = \sum_{x \in A} \frac{m!}{x_1 !...x_n !} 			p_1^{x_1}...p_n^{x_n}
	\end{equation}
	</center>
	```

## 关于颜色,字号,和大小
* .\*.pynb文件(编辑工具为Pycharm,Jupyter Notebook)中可以使用html代码对公式颜色,字号和大小进行设置,如下所示:
```markdown
<font color='red' size=4 face='Consolas'>

$ x^2 + 2*2 + 1 二次函数$

$$ x^2 + 2*2 + 1 二次函数 $$

\begin{align}
x &= t + \cos t + 1\\
y &= 2 \sin 5
\end{align}

</font>
```
* Typora中支持较差,不建议使用

### 关于带有矩阵多行对齐公式
##### Typora中显示
```Latex
\begin{align}
\frac{\partial y}{\partial X} &= 
\begin{bmatrix}
\frac{\partial y}{\partial x_{11}} & \dots  & \frac{\partial y}{\partial x_{m1}} \\
\vdots                             & \ddots & \vdots \\
\frac{\partial y}{\partial x_{1n}} & \dots  & \frac{\partial y}{\partial x_{mn}} \\
\end{bmatrix} \\
&= \frac{\partial y}{\partial X^T}
\end{align}
```
##### Pycharm,Jupyter Notebook中显示
```Latex
\begin{align}
\frac{\partial y}{\partial X} &= 
\begin{bmatrix}
\frac{\partial y}{\partial x_{11}} & \dots  & \frac{\partial y}{\partial x_{m1}} \\
\vdots                             & \ddots & \vdots \\
\frac{\partial y}{\partial x_{1n}} & \dots  & \frac{\partial y}{\partial x_{mn}} \\
\end{bmatrix} \\\\\ %才可正常进行换行
&= \frac{\partial y}{\partial X^T}
\end{align}
```