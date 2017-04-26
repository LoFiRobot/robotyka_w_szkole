# Konfiguracja komputera

<iframe width="560" height="315" src="https://www.youtube.com/embed/AFn3ImYIUEc?ecver=1" frameborder="0" allowfullscreen></iframe>


Aby móc korzystać ze wszystkich funkcji zestawu EDUBOX konieczne jest zainstalowanie na komputerze następujących programów i wtyczek:
* Przeglądarka internetowa [CHROME](https://www.google.pl/chrome/browser/desktop/)
* [Arduino IDE](https://www.arduino.cc/en/Main/Software)
* Wtyczka [LOFI Robot ScratchX](https://chrome.google.com/webstore/detail/lofi-robot-scratchx/opdjdfckgbogbagnkbkpjgficbampcel) dla przeglądarki CHROME




###ARDUINO IDE

<a href="https://www.arduino.cc/en/Main/Software" target="_blank">LINK DO POBRANIA PROGRAMU</a>

ARDUINO IDE to główny program towarzyszący płytce Arduino. Jego główna funkcja to edytor umożliwiający pisanie skryptów i wgrywanie ich na płytkę Arduino. Instalacja ADUINO IDE jest konieczna w celu instalacji sterowników do płtyki Arduino na Twoim komputerze.

**WINDOWS**
- po zainstalowaniu ARDUINO IDE i podłączeniu sterownika do komputera system powinien automatycznie zainstalować sterowniki do płytki - jeśli nie jesteś pewny czy sterowniki zainstalowane są poprawnie wyszukaj sterownik w **PANEL STEROWANIA -> MENEDŻER URZĄDZEŃ -> PORTY (COM i LPT) -> ARDUINO LEONARDO**. Zapamiętaj nazwę portu jaką system przypisze do sterownika (COM z cyfrą od 1 do 20, np. COM9)




###Konfiguracja wtycznik LOFI Robot ScratchX CHROME

![](chrome_scratch.png)


### Instrukcja obsługi:


1. Uruchom przeglądarkę Chrome
2. Zainstaluj aplikację <a href="https://chrome.google.com/webstore/detail/lofi-robot-scratchx/opdjdfckgbogbagnkbkpjgficbampcel?utm_source=chrome-ntp-icon" target="_blank">LOFI ROBOT ScratchX</a> z Chrome Web Store
3. Na sterownik LOFI Brain wgraj skrypt do komunikacji ze Scratchem - umożliwiający komunikację przez kabel USB i moduł Bluetooth
4. Jeśli planujesz używać komunikacji bluetooth sparuj moduł bluetooth 2.0 z komputerem (hasło parowania: 1234)
5. Uruchom w przeglądarce Chrome aplikację <strong>LOFI Robot ScratchX</strong>, i z zakładki SERIAL PORT USB (również w przypadku bluetooth!) wybierz w odpowiedni port do komunikacji i kliknij przycisk <strong>CONNECT
</strong>
6. Uruchom ScratchX klikając przycisk <strong>OPEN SCRATCHX</strong>



> Większość laptopów posiada wbudowaną możliwość komunikacji bluetooth. Jeśli korzystasz z komutera stacjonarnego, który nie posiada wbudowanej anteny do komunikacji bluetooth, w prosty sposób można dodać mu tą funkcję przy pomocy taniego adaptera bluetooth 2.0 podłączanego do portu USB, większość tego typu adapterów jeśłi działa w standardzie bluetooth 2.0 będzie kompatybilna z modułem bluetooth dołączonym do zestawu EDUBOX. 




Aby sterownik LOFI Brain komunikował się ze Scratchem do pamięci sterownika wgrać musimy specjalny skrypt. Poniżej znajdują się dwie wersje tego skryptu - dla komunikacji przez kabel USB oraz przez moduł bluetooth.


<h1>LOFI Robot ScratchX - połączenie przez USB i moduł Bluetooth 2.0</h1>

<iframe src="https://create.arduino.cc/editor/LoFiRobot/e1d2069e-0c4a-42e1-a782-1e0bd958a00f/preview?embed" style="height:510px;width:100%;margin:10px 0" frameborder="0"></iframe>

