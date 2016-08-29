# Konfiguracja komputera

Aby móc korzystać ze wszystkich funkcji zestawu EDUBOX konieczne jest zainstalowanie na komputerze następujących programów i wtyczek:


<h1>ARDUINO IDE</h1>

<a href="https://www.arduino.cc/en/Main/Software" target="_blank">LINK DO POBRANIA PROGRAMU</a>

ARDUINO IDE to główny program towarzyszący płytce Arduino. Jego główna funkcja to edytor umożliwiający pisanie skryptów i wgrywanie ich na płytkę Arduino. Nawet jeśli na początku nie będziesz z niego korzystać instalacja AADUINO IDE jest konieczna w celu instalacji sterowników do płtyki Arduino na Twoim komputerze.

<h1>CODEBENDER.CC</h1>

<a target="_blank" href="http://www.codebender.cc">LINK DO SERWISU</a>

Codebender to bardzo przydatny serwis internetowy, który umożliwia programowanie Arduino z poziomu przeglądarki internetowej. Korzystanie z niego nie jest niezbędne do programowania Arduino, pozwala jednak bardzo uprościć pracę dlatego zalecamy założenie konta w tym serwisie.

Przykłady skryptów Arduino na naszej stronie podawane są w formie okien z serwisu Codebender takich jak to:

<iframe style="height: 510px; width: 100%; margin: 10px 0 10px;" allowTransparency="true" src="https://codebender.cc/embed/sketch:166817" frameborder="0"></iframe>

Dzięki temu aby wgrać kod na Arduino wystarczy kliknąć zielony przycisk <strong>RUN ON ARDUINO</strong>
Jeśli chcesz pobrać ten skrypt kliknij przycisk DOWNLOAD i ściągnięty plik (po odzipowaniu) uruchom w programie Arduino IDE.

Aby móc korzystać z Codebendera konieczna jest jego konfiguracja i zainstalowanie odpowiedniej wtyczki.
Instaluje się ona automatycznie podczas zakładania konta w serwisie.


##Konfiguracja wtycznik LOFI Robot ScratchX CHROME

![](chrome_scratch.png)

Instrukcja obsługi:
1. Uruchom przeglądarkę Chrome
2. Zainstaluj aplikację <a href="https://chrome.google.com/webstore/detail/lofi-robot-scratchx/opdjdfckgbogbagnkbkpjgficbampcel?utm_source=chrome-ntp-icon" target="_blank">LOFI ROBOT ScratchX</a> z Chrome Web Store
3. Na sterownik LOFI Brain wgraj odpowiednią wersję skryptu <strong>FIRMATA</strong> - zwykłą (komunikacja przez port USB) lub do komunikacji bluetooth
4. Sprauj moduł bluetooth 2.0 z komputerem (hasło parowania: 1234)
5. Uruchom w przeglądarce Chrome aplikację <strong>LOFI Robot ScratchX</strong>, wybierz w niej odpowiedni port do komunikacji i kliknij przycisk <strong>CONNECT
</strong>6. Uruchom ScratchX klikając przycisk <strong>OPEN SCRATCHX</strong>


<strong>UWAGA - Aplikacja jest w wersji BETA</strong>
- nie działa obsługa czujnika odległości
- nie działa obsługa serwomotorów
- odczyt pinów analogowych (INPUT) momentami jest opóźniony (problemy szczególnie nasilają się przy komunikacji bluetooth) - prawdopodobnie ze względu na ograniczenia przepustowości Chrome.serial API


<h1>LOFI FIRMATA - USB</h1>
<iframe style="height: 510px; width: 100%; margin: 10px 0 10px;" allowTransparency="true" src="https://codebender.cc/embed/sketch:166817" frameborder="0"></iframe>

<h1>LOFI FIRMATA - BLUETOOTH</h1>

Jeśli masz problem z wgraniem poniższego kodu przy pomocy CODEBENDERA skopiuj go i wgraj przy pomocy programu ARDUINO IDE

<iframe style="height: 510px; width: 100%; margin: 10px 0 10px;" allowTransparency="true" src="https://codebender.cc/embed/sketch:345964" frameborder="0"></iframe> 

