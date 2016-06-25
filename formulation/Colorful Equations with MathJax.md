<script type="text/x-mathjax-config">
  MathJax.Hub.Config({ TeX: { extensions: ["color.js"] }});
</script>

<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>

#色彩标注法
Stuart Riffle给出了对傅里叶变换的一个绝佳解释。在他的公布内容中有许多精彩的图片，但是其中的顶点是他关于离散傅里叶逆变换公式的解释：

![Mou icon](figure1.png)

真是一个棒极了的展示！我的第一个想法是，更多的方程式应该有这样专注于读者理解的优雅的解释上。我希望能够以这种风格来给出如此清晰的解释：

$$\textcolor{Purple}{X}_\textcolor{Green}{k}
=\textcolor{Magenta}{\frac{1}{N}\sum_{n=0}^{N-1}}
\textcolor{Blue}{x_n}
\textcolor{Red}{e}^
{\textcolor{Red}{i}\textcolor{Orange}{2\pi} 
\textcolor{Green}{k}
\textcolor{Magenta}{\frac{n}{N}}
}.$$

为了发现</font> <font color=Green>特定频率下的</font><font color=Purple>能量，</font> <font color=Green>以那个频率</font><font color=Orange>环绕一个圆</font> , <font color=Red>旋转</font><font color=Blue>你的信号，</font>并且<font color=Magenta>沿着该路径平均地分配一束点。</font>

**与机械化翻译公式的结合**：色彩标注法中运用色彩的不同来分析傅里叶公式的结构，更加清晰的表达了各个因子在公式中所处的位置及其作用。而在钟平老师的机械化翻译公式中，我们同样可以运用到这个方法来分析句子的成分。先运用不同的颜色来标示出句子中的主干--即主语，谓语及宾语；继而再用其余颜色来标示出定语及状语，可继续细分为介词短语，分词短语以及从句。用不同的颜色来强调出句子的成分，更便于细致分析，并运用机械化公式按照中英逻辑的不同，合理地翻译为中文。

**Remark:**

1. Html color setting  
		<font color=Blue>Blue</font> 
		 <font color=Brown>Brown</font> 
		 <font color=Cyan>Cyan</font> 
		 <font color=Green>Green</font> 
		 <font color=Grey>Grey</font> 
		 <font color=Magenta>Magenta</font> 
		 <font color=Orange>Orange</font> 
		 <font color=Yellow>Yellow</font> 
		 <font color=Purple>Purple</font> 
2. The raw equation is $$X_k=\frac{1}{N}\sum_{n=0}^{N-1}x_ne^{i2\pi k \frac{n}{N}}.$$
3. Reference: [Colorful Equations With MathJax](http://adereth.github.io/blog/2013/11/29/colorful-equations/)