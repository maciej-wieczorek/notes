# Datagram
[[Pakiet]] wysłany w sieci bez wcześniejszego nawiązania połączenia

Zmienna długość (20-65535 bajtów)
Składa się z nagłówka i danych

### Nagłówek
- VER - wersja (4 lub 6)
- HLEN - długość nagłówka (wartość * 4 bajty)
- Service type - typ usługi
- Total length - całkowita długość datagramu wraz z nagłówkiem
- Identification - 16 bitów identyfikacyjnych (ważne gdy datagram jest [[Fragmentacja|fragmentowany]])
- Flags - 3 flagi z czego 2 się wykorzystuje
- Fragmentation offset - offset do fragmentacji (* 8 bajtów), jak datagram jest składany to offset mówi gdzie wstawić dany fragment
- [[Time to live]]
- Protocol - tu umieszczany jest protoków [[Warstwa sieciowa|warstwy sieciowej]]
- Header checksum - [[Suma kontrolna|suma kontrolna]] nagłówka
- Source IP address
- Destination IP address
- Options + padding - żadko używane opcje

[[Sieci komputerowe]]