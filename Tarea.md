# Tarea
\documentclass{article}
\usepackage[spanish]{babel}
\usepackage[utf8]{inputenc}
\usepackage{amsmath,amsthm,amsfonts}
\usepackage{latexsym,amssymb}
\newcommand{\li}{{\ensuremath{\displaystyle\lim_{x\to a}}}}
\newtheorem{teor}{Teorema}
\begin{document}
\section{1.1.1 Medida}

-Por espacio medible entendemos un par ordenado ($\Omega$, B) que consta de un conjunto $\Omega$ y un o-álgebra B de subconjuntos de $\Omega$. Un subconjunto A de $\Omega$ se llama medible si $A \in B$.

-Una medida $\mu$ en un espacio medible ($\Omega$, B) es una función $\mu$:\\
$B\to \mathbb [0,\infty]$ que  satisface:\\

$\mu$($\phi$) = 0\\

$\mu (\displaystyle\bigcup_{i}^\infty E_i )= \displaystyle\sum_{i}^{\infty} \mu (E_{i})$

para cualquier sucesión $\{E_{i}\}$ de conjuntos medibles disjuntos, es decir $E_{i} \cap$\\
$E_{j} = \emptyset, E_{i} \in B,i \neq j$

($\Omega$, B, $\mu$) se llama espacio de medida.\\

\section{Teorema 2} Los siguientes afirmaciones son equivalentes para un grupo G.\\
1. P(G) = 1   \\      
2. G es abeliano   \\  
3. Z(G) = G    \\      
4. G' = \{1\} \\
5. $C_{G}(a)$ =G para todo  $a\in G$  \\
6.G/ G' $\cong$G \\   
\section{Demostración.} Si P(G) = 1,entonces $|L(G)|= |G |^2$.Luego $L(G)=G^2$ y esto significa xy = yx para todo $x,y\in G$ .Así G es un grupo abeliano. Es inmediato observar que el razonamiento inverso también es cierto, lo que prueba que 1. es equivalente a 2.

Según este resultado, para tener grados de conmutatividad diferentes de 1 debemos analizar grupos no abelianos.
$\hfill\blacksquare$
\end{document}
