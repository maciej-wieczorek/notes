# [[Cisco]] IOS
[[System operacyjny]] na [[Router Cisco|routerach Cisco]].

### Trypy powłoki
- tryb użytkownika (>)
- tryb uprzywilejowany (#)
- tryk konfiguracyjny ((config))

### Skróty klawiszowe:
- Ctrl-z: confnięcie się do trybu uprzywilejowanego
- Ctrl-r: refresh pisanej lini
- Ctrl-alt-6: zatrzymanie programu

### Komendy trybu użytkownika
- ping
- tracert
## Komendy trybu uprzywilejowanego
- disable - wyjście z trypu uprzywilejowanego (do użytkownika)
- configure terminal - wejście do trybu konfiguracyjnego
- telnet
- show interfaces
- show running-config
- show ip interface brief
- show ip route
- show cdp neighbors
- show ip route
- traceroute 172.16.32.11 numeric
## Komendy trybu konfiguracyjnego
- hostname Nazwa - ustawia [[Hostname|hostname]]
- ip route
- ip route 172.16.0.0 255.255.0.0 10.222.0.1
- ip route 0.0.0.0 0.0.0.0 192.168.51.17
- no ip route 172.16.0.0 255.255.0.0
- router
- interface FastEthernet 0/1 - przejście do trybu konfiguracji interfejsu

### Komendy trybu konfiguracji interfejsu
- ip address 192.168.0.100 255.255.255.0 - konfiguruje [[Adres IP|adres ip]]
- no shutdown - włącz [[Interfejs logiczny|interfejs]]

### Komendy uniwersalne
- exit - wychodzi o jeden tryb w górę, działa do trybu uprzywilejowanego
- end - cofa do trybu uprzywilejowanego
- do - pozwala wykonać komendę z wcześniejszego poziomu
- ? - podpowiada komendy
- no - odwraca akcje (np. no shutdown)

Komendy można skracać póki są jednoznaczne.

[[Sieci komputerowe]]