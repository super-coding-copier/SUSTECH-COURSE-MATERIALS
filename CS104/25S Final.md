# 1 谓词逻辑，判断formula是不是well formed
简单
# 2 判断Logical equivalence
用 truth table 即可
# 3 Adequate Set
The truth table for  $\downarrow$

| p   | q   | p$\downarrow$q |
| --- | --- | -------------- |
| 1   | 1   | 0              |
| 1   | 0   | 0              |
| 0   | 1   | 0              |
| 0   | 0   | 1              |

Show that  $\{ \downarrow \}$ is an adequate set.
作业里有一道基本一样的题
# 4 Tautology, Contradiction or Neither(有5个)
1. $p\to(q\to p)$
2. $(a\to \neg a)\to a$
3. $(p\to(q\to r))\to((p\to q)\to(p\to r))$
4. 


# 4 判断first order logic 中的well formed

# 5 
$$
\begin{align}
&1.  \forall x \exists y
\end{align}
$$

# 7 判断题（5个？）
1. A sound deduction system can proof every formula that is not a tautology.
2. The completeness of a system guarantees that every proof formula is valid.
3. Every formula in resolution logic is equivalent to a unique CNF.
4. The Hoare triple P-C-Q is true if P cannot be satisfied under all circumstances.

# 8 ND proof(一共4个)
1. $\neg p\lor q\vdash p\to q$
2. $\exists x(P(x)\lor Q(x))\vdash\exists xP(x)\lor \exists xQ(x)$
3. $\forall x(P(x)\to Q(x))\vdash\forall xP(x)\to \forall xQ(x)$
4. $\forall x\neg P(x)\vdash\neg \exists xP(x)$


