# [[Prawdopodobieństwo]] warunkowe
### Wzór
$$P(A\mid B)=\frac{P(A\cap B)}{P(B)}$$
Prawdopodobieństwo zajścia [[Zdarzenie losowe|zdarzenia]] A pod warunkiem zajścia zdarzenia B

### Wyprowadzenie
Dla [[Prawdopodobieństwo klasyczne|prawdopodobieństwa klasycznego]]:
$$ P(A \mid B) = \frac{|A \cap B|}{|B|} = \frac{\frac{|A \cap B|}{|\Omega|}}{\frac{|B|}{|\Omega|}} = \frac{P(A \cap B)}{P(B)} $$
Jeśli [[Zasada nierozróżnialności|zasada nierozróżnialności]] nie zachodzi to możemy nadal myśleć o prawdopodobieństwie [[Zdarzenie losowe|zdarzenia losowego]] jako o sumie prawdopodobieństw wszystkich jego [[Zdarzenie elementarne|zdarzeń elementarnych]].
Inaczej: każde [[Zdarzenie elementarne|zdarzenie elementarne]] ma swoją wagę, waga [[Przestrzeń zdarzeń elementarnych|przestrzeni zdarzeń elementarnych]] jest równa 1, a waga [[Zdarzenie losowe|zdarzenia losowego]] to suma wag jego [[Zdarzenie elementarne|zdarzeń elementarnych]].
Patrz przykład 2.

### Intuicja
Po tym jak wiemy, że zaszło [[Zdarzenie losowe|zdarzenie]] $B$, to redukujemy [[Przestrzeń zdarzeń elementarnych|przestrzeń zdarzeń elementarnych]] do $B$. Więc liczą się tylko te [[Zdarzenie elementarne|zdarzenia elementarne]] które należą zarówno do $A$ i $B$ 

### Symetria
$$P(B\mid A)=\frac{P(A\cap B)}{P(A)}$$
,czyli:
$$P(A\cap B)=P(B)P(A\mid B)=P(A)P(B\mid A)$$
### Przykład
- Jaka jest szansa wylosowania co najmniej 5 oczek w rzucie kostką ([[Zdarzenie losowe|zdarzenie losowe]] $A$) jeśli wypadła nieparzysta liczba oczek (zdarzenie losowe $B$)
![](img/prawdopodobienstwo_warunkowe1.PNG)
$A=\{\omega_5, \omega_6\}$
$B=\{\omega_1, \omega_2, \omega_3\}$
$A\cap B=\{\omega_5\}$

$$P(A\mid B)=\frac{\vert A\cap B\vert}{|B|}=\frac{1}{3}$$
- To samo, ale dla nieuczciwej kostki
![](img/prawdopodobienstwo_warunkowe2.PNG)
$A=\{\omega_5, \omega_6\}\qquad P(A)=0.6$
$B=\{\omega_1, \omega_2, \omega_3\}\quad P(A)=0.7$
$A\cap B=\{\omega_5\}\qquad P(A)=0.5$

$$P(A\mid B)=\frac{P(A\cap B)}{P(B)}=\frac{5}{7}$$
[[Metody probabilistyczne]]