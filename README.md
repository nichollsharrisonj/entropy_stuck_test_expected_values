Jupyter notebook to compare measured vs expected failures of entropy stuck test $\Delta_2$ and $\Delta_3$ given an arbitrary stream of time deltas.

Definitions:

$d_i = t_i - t_{i-1}$

$p(\Delta_2) = p(d_i = d_{i-1})$

$p(\Delta_3) = p(d_i - d_{i-1} = d_{i-1} - d_{i-2})$

Computes expected $\Delta_{2e}$ and $\Delta_{3e}$ based on observed distribution with:

$p(\Delta_{2e}) = \sum_k{\ p_k^2}$ where $p_k = p(d_i = k) =  {c_k \over N}$

And

$p(\Delta_{3e}) = \sum_{a,b,c:\  a + c = 2b}{p_a \times p_b \times p_c}$

To compare with measured $\Delta_2$ and $\Delta_3$
