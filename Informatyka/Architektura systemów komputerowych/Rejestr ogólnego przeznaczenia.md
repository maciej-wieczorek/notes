# Rejestr ogólnego przeznaczenia
Zadaniem tych [[Rejestr|rejestrów]] jest przechowywanie danych

W praktyce (architektura Intela):
- AX ([[Akumulator|akumulator]]): operacje logiczne
- BX: adresowanie pamięci
- CX: licznik w pętlach
- DX: przekazywanie i odbieranie danych z portów wejścia-wyjścia

Algorytm najlepiej projektować tak, aby odpowiedznie dane znalazły się w odpowiedznich rejestrach, aby unikną wykonywania operacji [[MOV]]

W [[Architektura RISC|RISC]] takich rejestrów może być nawet 200

[[Architektura systemów komputerowych]]