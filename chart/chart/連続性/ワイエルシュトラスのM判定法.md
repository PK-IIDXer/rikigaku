# 定理
$S$を集合とし、各自然数$n$に対し$f_n:S\to\mathbb{R}^m$を写像とする。実数列$\{a_n\}_{n\in\mathbb{N}}$が存在して、任意の$n\in\mathbb{N}$に対して$a_n\geq0$を満たし、かつ、任意の$n\in\mathbb{N}$と任意の$x\in S$に対して$|f_n(x)|\leq a_n$を満たすとする。さらに$\sum_{n=1}^\infty a_n$が収束するとするならば、$\sum_{n=1}^\infty f_n(x)$は[[一様収束]]する。
# 証明
[[コーシーの収束判定法(一様収束)]]を使う。任意の$\varepsilon>0$をとる。$\sum_{n=1}^\infty a_n$は収束するから、[[コーシーの収束判定法]]より、ある$N(\varepsilon)\in\mathbb{N}$が存在して、任意の$n>m>N(\varepsilon)$に対して$$|a_{m+1}+\cdots+a_n|<\epsilon$$を満たす。各$a_i$は正であるから、$$
a_{m+1}+\cdots+a_n=|a_{m+1}+\cdots+a_n|<\varepsilon
$$が従う。ゆえに任意の$x\in S$に対して、三角不等式より$$
\begin{align*}
|f_{m+1}(x)+\cdots+f_n(x)|&\leq|f_{m+1}|+\cdots+|f_n(x)|\\
&\leq a_{m+1}+\cdots+a_n\\
&<\varepsilon
\end{align*}
$$従って[[コーシーの収束判定法(一様収束)]]より、$\sum_{n=1}^\infty f_n(x)$は[[一様収束]]する。
