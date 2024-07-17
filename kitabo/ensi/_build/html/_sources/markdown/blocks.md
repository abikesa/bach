
# Blocks & Labels

                              1. f(t)
                                    \
                         2. S(t) -> 4. X -> 5. b -> 6. SV 
                                    /
                                    3. h(t)

### Biological: Anxiety(t) 1, 2, 3
- $f(t)$
- $S(t)$
- $h(t)=\frac{f(t)}{S(t)}$

### Politics: GoT 4
- $\displaystyle X$

### Selfish: Will 5, 6


```{margin}
This is a margin note.
```

```{note}
This is a general note.
```

```{tip}
Here's a helpful tip.
```

```{warning}
Warning: Proceed with caution!
```

```{caution}
Caution: Pay attention to this.
```

```{danger} $h(t)=\frac{f(t)}{S(t)}$
Danger: Potential hazard ahead!

                          1. f(t)
                                \
                     2. S(t) -> 4. X -> 5. b -> 6. SV 
                                /
                                3. h(t)
```



```{attention}
Attention: Important information highlighted.
```

```{important}
Important: Crucial information to note.
```

```{hint}
Hint: A small hint to help you out.
```

```{sidebar}
Sidebar: Extra information on the side.
```


Got it! To make the variable \( X \) appear larger in LaTeX, you can use the `\displaystyle` command within a math environment to make it larger than the standard inline math size. Here is how you can do it:

```latex
\[ \displaystyle X \]
```

If you want it even larger, you can use one of the font size commands such as `\Huge`, `\huge`, `\LARGE`, `\Large`, `\large`, `\normalsize`, `\small`, `\footnotesize`, `\scriptsize`, or `\tiny`. For example:

```latex
{\Huge X}
```

Here is an example with different sizes:

```latex
\documentclass{article}
\begin{document}

\[
\text{Normal size: } X
\]

\[
\text{\Huge Large size: } X
\]

\[
\text{\LARGE Larger size: } X
\]

\[
\text{\huge Even larger size: } X
\]

\[
\text{\Huge Largest size: } X
\]

\end{document}
```

Each command modifies the size of the variable \( X \) accordingly.