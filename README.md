# 王少东 202201212813
## cv课第5次作业
### 各变量的导数表达式

$$\frac{\partial f}{\partial W_2}=h_{sigmod} \cdot2.0\times(y_{pred}-y)$$

$$\frac{\partial f}{\partial b_2}=2.0\times(y_{pred}-y)$$

$$\frac{\partial f}{\partial h}=h(1-h)\cdot W_2^T\cdot 2.0\times(y_{pred}-y)$$

$$\frac{\partial f}{\partial W_1}=[X^T\cdot(1-h)-h\cdot X^T]\cdot W_2^T \cdot 2.0\times(y_{pred}-y)$$

$$\frac{\partial f}{\partial b_2}=[(1-2h)]\cdot W_2^T \cdot 2.0\times(y_{pred}-y)$$