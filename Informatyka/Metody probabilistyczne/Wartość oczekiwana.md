# Wartość oczekiwana

$$E(X)=\sum_ix_iP(X=x_i)$$
$$E(X)=\sum_xxP(X=x)$$
### Wyjaśnienie
Wartość oczekiwana to [[Średnia ważona|średnia ważona]] po zbiorze $\{x_1,x_2,\ldots\}$ z wagami równymi $P(X=x_i)$
Wartość oczekiwana: wartość przeciętna, wartośc średnia zmiennej losowej $X$

### Oznaczenie
$E(X)$ lub $EX$

### Własności
- Jeśli $X$ przyjmuje tylko wartości większe bądź równe a, to $EX \geq a$
$$EX=\sum_xxP(X=x)\geq \sum_xaP(X=x)=a\sum_xP(X=x)=a$$
- Liniowość wartości oczekiwanej: $E(aX+b)=aE(X)+b$
$g(x)=ax+b$
$$E(aX+b)=E\bigl(g(X)\bigr)=\sum_xg(x)P(X=x)=\sum_x(ax+b)P(X=x)=a\biggl(\sum_xxP(X=x)\biggr)+b\biggl(\sum_xP(X=x)\biggr)=a\cdot EX+b \cdot 1=aEX+b$$

[[Metody probabilistyczne]]