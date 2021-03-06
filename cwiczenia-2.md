Ustawianie parametrów sieci
---------------------------

![alt text][network]

[network]: ./network.png "Logo Title Text 2"

1. na 1 z komputerów zainstaluj oprogramowanie ``http-chat`` dostępne pod adresem ``https://github.com/jkanclerz/http-chat``

Wejściowe parametry sieci
-------------------------
| Parametr | wartość | komentarz(opcionalny) |
| ------------- |:-------------:| -----:|
|   PC 1 | CentOS 1 
| IP - address | 10.0.2.15 | |
| MASKA | 10.0.2.15/24 | |
|   |  | |
| PC 2  | CentOS 2 | |
| IP - address | 10.0.2.4 | |
| MASKA  | 10.0.2.4/24| |

Weryfikacja połączenia

Polecenie
ping 10.0.2.4

Efekt
64 bytes from 10.0.2.4: icmp_seq ttl=64 time=0.415 ms

Statyczna konfiguracja parametrów połączenia
Wejściowe parametry sieci
-------------------------
| Parametr | wartość | komentarz(opcionalny) |
| ------------- |:-------------:| -----:|
|   PC 1 |  
| IP - address  | 192.168.10.10 | |
| MASKA  | 255.255.255.0 | |
|   |  | |
| PC 2  |  | |
| IP - address  | 172.16.100.100 | |
| MASKA  | 255.255.0.0 | |

Weryfikacja połączenia

Polecenie
```
```

Efekt
```
```

Nowa statyczna konfiguracja 

-------------------------
| Parametr | wartość | komentarz(opcionalny) |
| ------------- |:-------------:| -----:|
|   PC 1 |  
| IP - address  |  | |
| MASKA  |  | |
|   |  | |
| PC 2  |  | |
| IP - address  |  | |
| MASKA  |  | |

Weryfikacja połączenia

Polecenie
```
```

Efekt
```
```

Warto wiedzieć
--------------

-------------------------
| Parametr | wartość | komentarz(opcionalny) |
| ------------- |:-------------:| -----:|
| Lokalizacja pliku z konfiguracją sieci| | |
| UP -> Wyłączenie interfejsu sieciowego| ifup enp0s3 | |
| DOWN -> Włączenie interfejsu sieciowego| ifdown enp0s3 | |
| Sprawdzenie obecnych parametrów | nmcli | |
| lista wszystkich interfejsów | | |
| Które interfejsy jakie porty słuchają | ip a | |
