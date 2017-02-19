---
layout: post
title: Testing LaTeX equation references
---

Here is an equation.

$$
\begin{align}
a &= b + c \label{eq:eq1} \\
d &= e + f \label{eq:eq2}
g &= h + i \nonumber
\end{align}
$$

I want to cite $\ref{eq:eq1}$ or $\eqref{eq:eq1}$.

$$
\begin{aligned}
f(t) &= p \lambda t^{p-1} \exp\{-\lambda t^p \} \\
S(t) &= \exp\{-\lambda t^p \}
\end{aligned}
$$

How does bold math work: $\boldsymbol\beta$, $\pmb{\beta}$.


Can we define now commands?

$$
\newcommand{\bbeta}{\pmb{\beta}}
$$

$$
\begin{align}
\textbf{X}  &=  \bbeta
\end{align}
$$

