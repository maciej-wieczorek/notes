# Fragmentacja
[[Datagram]] może mieć 65k bajtów, a ramka tylko 1.5 bajtów.
Taki datagram trzeba fragmentować

Tylko dane są fragmentowane.
Nagłówki są powielana, ale pole z offsetem i flagami się zmienia

### Flagi
- D: Do not fragment
- M: More fragments (0 - ostatni fragment)

[[Sieci komputerowe]]