$$
```latex

\newcommand\showdiv[1]{\overline{\smash{\hstretch{.5}{)}\mkern-3.2mu\hstretch{.5}{)}}#1}}
\let\ph\phantom
\begin{document}
\setstackgap{S}{1.5pt}
\stackMath\def\stackalignment{r}
\(
\stackunder{%
  5 \stackon[1pt]{\showdiv{12345}}{2469}%
}{%
  \Shortstack[l]{{\underline{10}} \ph{1}23 {\ph{1}\underline{20}} \ph{12}34 {\ph{12}\underline{30}} %
   \ph{123}45 {\ph{123}\underline{45}} \ph{1234}0}%
}
\)
\end{document}
```
$$