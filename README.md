# JupyterNotebook-usage
Jupyter Notebook用法

```
  行当前代码区块的快捷键为 [Ctrl+Enter] 。
  运行当前代码区块并转到下一区块的快捷键为 [Shift+Enter] 。

  当点击代码区块编辑框以外的部分时，区块左侧边框颜色会变为蓝色，此时点击目标区块左侧，
  按 [b] 可在目标区块下方新增区块，
  按 [a] 可在目标区块上方新增区块。
  
  切换代码行号的显示/隐藏： [Shift+L]
  删除当前区块： 连续按两次 [d]
  复制、剪切、粘贴区块： [c/x/v]
  查找并替换区块内容： [f]
  设置为标记（Markdown）格式： [m]
  设置为代码（Code）格式: [y]
  
  
```

# Latex

## 省略号
  \dots
  $\dots$

### 在latex中，连续输入三个句号（即 .）来表示省略号是不规范的，具体的：

    \cdots 是横向的居中的省略号
    \vdots 是竖向的省略号
    \ddots 是对角线方向的省略号
    \ldots  是跟文本底线对齐的省略号
   
$$
    Y=\{y_1, y_2, \ldots, y_n\},\\
    \begin{bmatrix}
    	x_{11} & x_{12}  & \cdots   & x_{1m}   \\
    	x_{21} & x_{22}  & \cdots   & x_{2m}  \\
    	\vdots & \vdots  & \ddots   & \vdots  \\
    	x_{n1} & x_{n2}  & \cdots\  & x_{nm}  \\
    \end{bmatrix}
$$
    

## 公式自定义编号 
    \tag{3.1}
    
# 
\binom{n}{r}
$$ \binom{n}{r} $$
