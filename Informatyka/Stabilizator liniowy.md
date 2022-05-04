# [[Stabilizator napięcia|Stabilizator]] liniowy
Prosty i tani [[Stabilizator napięcia|stabilizator napięcia]].

### Parametry
- LDO - low [[Dropout|dropout]], wymaga małego [[Dropout|dropoutu]]
- Regulowany - można regulować [[Napięcie|napięcie]] wyjścia
- Nieregulowany - [[Napięcie|napięcie]] wyjścia jest ustalone przez producenta

### Wady
- wydziela ciepło, proporcjonalne do różnicy [[Napięcie|napięć]] (wejście/wyjście) i pobieranego [[Natężenie|prądu]],
- nie potrafi wytworzyć [[Napięcie|napięcia]] wyższego niż wejściowe.

## [[Moc]] tracona
$$P=(U_\text{we}-U_\text{wy})\cdot I$$
gdzie:
- $U_\text{we}$ - [[Napięcie|napięcie]] wejściowe
- $U_\text{wy}$ - [[Napięcie|napięcie]] wyjściowe
- $I$ - [[Natężenie|prąd]] pobierany z wyjścia stabilizatora

Przyczyną mocy traconej jest [[Dropout|dropout]].

[[Elektronika]]