# DODATKOWE PRZYKŁADY


Wszystkie linki działają w przeglądarce CHROME z rozrzerzeniem LOFI Robot ScratchX

https://chrome.google.com/webstore/detail/lofi-robot-scratchx/opdjdfckgbogbagnkbkpjgficbampcel?utm_source=chrome-ntp-icon


### AUTOMATYCZNA LAMPA

Proste ćwiczenie wprowadzające warunek **JEŚELI/WPRZECIWNYM RAZIE - IF/ELSE**

Lampka (symbolizowana przez diodę LED) zapalająca się automatycznie gdy poziom światła mierzony przez czujnik natężenia światła spadnie poniżej zadanego poziomu.

Podłączenie modułów:
- czujnik światła - INPUT1
- dioda led - OUTPUT1


http://www.lofirobot.com/scratchx/?url=http://lofirobot.com/scratchx/examples/automatyczna_lampa.sbx#scratch


### INSTRUMENT MUZYCZNY

Instrument muzyczny na kontrolowany przy pomocy czujnika światła.

Ćwiczenie - INSTRUMENT MUZYCZNY

Czujniki:
- czujnik światła podłączony do INPUT1
- potencjometr podłączony do INPUT3

Instrument muzyczny, którego barwa (rodzaj instrumentu) kontrolowana jest przy pomocy potencjometru natomiast wysokość dźwięku kontroluje czujnik światła.

Im więcej światła - tym wyższy dźwięk, im mniej światła (zasłaniamy czujnik ręką) tym dźwięk niższy.

http://www.lofirobot.com/scratchx/?url=http://lofirobot.com/scratchx/examples/instrument_swiatlo_potencjometr.sbx#scratch


### CZUJNIK WILGOTNOŚCI GLEBY 

Czujnik i układa sygnalizujący czy należy podlać kwiatek doniczkowy.

Zadania:
- samodzielne skonstruowanie czujnika - z modułu PRZYCISK, kabli krokodylków i dwóch dużych gwoździ - gwoździe wbijamy w zięmię w doniczce - czujnik działa mierząc przewodność elektryczną gleby pomiędzy gwoździami

- kalibracja - odczytujemy wartość z czujnika, na podstawie testowych pomiarów ustalamy wartości graniczne - mierzymy i notujemy wskazania czujnika gdy ziemia jest sucha i po podlaniu kwiatka

- programujemy wizualizację pomiarów w SCRATCHU - wskaźnik pokazujący wartości na osi SUCHO-MOKRO, oraz wizualny obraz "samopoczucia kwiatka" sucho - kwiatek smutny, mokro - kwiatek wesoły

- programujemy wizualizację pomiarów przy pomocy elektronicznych modułów - odczyt z czujnika pokazany na mierniku napięcia, miganie diody przy odczycie SUCHO, pikanie buzzera przy odczycie BARDZO SUCHO

WERSJA ZAAWANSOWANA
- zaprogramowanie samodzielnego urządzenia działającego bez podłączenia do komputera - zaprogramowanie i wgranie kodu na Arduino
- owówienie procesu projektowego dla urządzenia elektronicznego
  - zdefiniowanie problemu
  - testy i przykładowe pomiary
  - wykonanie pierwszego prototypu - SCRATCH
  - wykonanie samodzielnie działającego prototypu - ARDUINO
  - omówienie - co można usprawnić aby urządzenie mogło być seryknie produkowane - wykonanie czujnika, obudowa, wykorzystanie samodzielnego modułu Arduino bez płytki LOFI Brain


### GRA ARKANOID

Zaprogramowanie gry polegającej na odbijaniu piłki na ekranie przy pomocy ruchomej paletki, sterowanej przy pomocy czujnika (odległości, światła lub potencjometru)

https://www.youtube.com/watch?v=CS5y9CEUl2g

### ALARM PRZECIWWŁAMANOWY

Stworzenie czujnika zwarciowego sygnalizującego np. otwarcie drzwi (dwie elektrody/blaszki np. z folii aluminiowej + moduł przycisk + kable krokodylki)

W momencie otworzenia drzwi alarm się włącza - generując miganie diody i piszczenie buzzera

Ćwiczenie można wykonać w zarówno w Scratchu jak i w formie samodzielnego urządzenia (wgrany kod na Arduino)

### PRZYCISK ZE WSZYSTKIEGO

