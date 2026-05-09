Jupyter notebook to compare measured vs expected failures of entropy stuck test (delta2 and delta3) given an arbitrary stream of time deltas.

Computes expected delta2 and delta3 based on observed distribution with:

$\Delta_2 = \sum_k{\ p_k^2}$ where $p_k = {c_k \over N}$

And

$\Delta_3 = \sum_{a,b,c:\  a + c = 2b}{p_a \times p_b \times p_c}$

To compare with measured $\Delta_2$ and $\Delta_3$
