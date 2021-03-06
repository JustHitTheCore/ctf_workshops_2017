# JHTC CTF Workshops / KNI Kernel AGH
This repo contains materials from [Just Hit the Core CTF team](https://ctftime.org/team/13830/) workshops organized thanks to [KNI Kernel](https://www.facebook.com/KNIKernel/) at [AGH University of Science and Technology](http://www.agh.edu.pl/en/).

As the workshops are in Polish, so are the materials here.

---

### Warsztaty w roku akademickim 2016/2017
* [lab1 - 21.11.2016](lab1.md) - wstęp do niskopoziomowego RE/pwn, debugowanie natywnego kodu, ramki stosu, buffer overflow itd.
* [lab2 - 28.11.2016](lab2.md) - dokończenie zadania z poprzednich warsztatów, pokazanie/omówienie ROPa, return2libc, roppera.
* 5.12.2016 - brak warsztatów ze względu na konferencję Code Europe ([prelekcja o CTFach - zapraszam](https://www.codeeurope.pl/pl/prelegenci/dominik-czarnota#/szczegoly/53?_k=b0m12c))
* [lab4 - 19.12.2016](lab3.md) - zobaczenie narzędzia [Veles](https://codisec.com/veles/) oraz [kryptografia - RSA](lab3/README.md)
* lab5 - 9.01.2017 - udział w prelekcji koła UKOD o nmap'ie; rozwiązywanie zadanek crypto z pwnerrank.com
* lab6 - 16.01.2017 - prezentacja o hashah, zadanie ROP z pwnerrank.com (patrz lab6/)
* lab7 - 23.01.2017 - przejrzenie zadań z kategorii Web oraz RE/pwn z [Teaser Insomni'Hack CTF](https://ctftime.org/event/382/tasks/). Między innymi:
  * omówienie architektury MIPS i tego jak zabrać się za inżynierię wsteczną binarek na nią (seria zadań bender_safe)
  * uzyskanie dostępu do niepoprawnie zabezpieczonego panelu administracyjnego serwera tomcat poprzez usługę proxy (zadanie smarttomcat)
  * analiza zapisu ruchu sieciowego (Wireshark; seria zadań Great Escape)
  * omówienie zabezpieczeń przeglądarek przed atakami XSS (nagłówki X-XSS-Protection, CSP, flagi ciasteczek HttpOnly oraz Secure; seria zadań Great Escape).
* lab8 - rozbiórka routera, zabawa z jego bootloaderem, shellem, dump filesystemu
* lab9 - 12.03.2017 - warsztaty całodniowe - inżynieria wsteczna i eksploitacja aplikacji na architekturę MIPS
* kolejne spotkanie - ??? do ustalenia

---

### Chcesz dołączyć?

Wymagania – przede wszystkim znajomość jakiegoś języka skryptowego (np. Python/Ruby) i chęć grania w CTFy.

Poza tym jedna z trzech rzeczy:
- podstawowa znajomość asemblera oraz znajomość C
- znajomość jakichś technologii webowych + podstaw web security
- znajomość podstaw kryptografii

### Rzeczy, które się przydadzą:
* laptop; dobrze byłoby mieć Linuxa
* Dostęp do sieci międzyuczelnianej eduroam (jeśli jesteś studentem)
* Gdb, Python
* Ida pro i/lub [Hopper](https://www.hopperapp.com/)
* [pwndbg](https://github.com/pwndbg/pwndbg)
* [pwntools do Pythona 2](https://github.com/Gallopsled/pwntools)
* http://angr.io/
* [Z3](https://github.com/Z3Prover/z3) - do Pythona (chyba nie ma w pipie (menedżerze paczek Pythona))
* Jakieś proxy do webów - Burp Suite / Fiddler / ZAProxy

### Inne materiały do nauki..:
- OverTheWire
- pwnable.kr
- rozwal.to
- crackmes.de
- https://cryptopals.com/ , kurs z crypto na Coursera
