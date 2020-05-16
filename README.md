# AntiCensorship Action
Sforkuj to repo, aby pomóc w zwalczaniu cenzury!

# 16 maja 2020
### Polskie Radio (Trójka) cenzuruje "Twój ból jest lepszy niż mój" Kazika.

15 maja 2020, utwór "Twój ból jest lepszy niż mój" wygrał głosowanie w Programie Trzecim Polskiego Radia. Kilka godzin później, redaktor naczelny Trójki Tomasz Kowalczewski ogłosił, że redakcja unieważniła głosowanie z powodu "wprowadzenia utworu spoza listy oraz manipulacji przy liczeniu głosów".
[źródło](https://www.facebook.com/219716348081/photos/a.10154083526778082/10159823799728082/?type=3)

Na stronie internetowej Polskiego Radia również nie znajdziemy wyników głosowania. Po wejściu na [artykuł poświęcony notowaniom](https://www.polskieradio.pl/9/4292/Artykul/2511579,LP3-za-nami-1998-notowanie) ukazuje się błąd 500 [[backup]](http://archive.is/Vx82y).
![błąd](https://i.imgur.com/PMpQJQW.png)
Nie jest to jednak błąd serwera, a celowe przekierowanie. Odpowiedzialny jest za to skrypt z 1942 linii kodu strony. 
![javascript](https://i.imgur.com/GrmfIta.png)
Po wyłączeniu obsługi JavaScript (np. przy użyciu rozszerzenia uBlock Origin lub NoScript) możemy bez problemu odwiedzić stronę.

Uszkodzona została również podstrona Polskiego Radia (lp3.polskieradio.pl). W tym przypadku z pliku konfiguracyjnego usunięty został znak `<`, przez co strona nie wczytuje się poprawnie [[backup]](http://archive.is/yCIEk).
![błąd](https://i.imgur.com/kpVIQoh.png)
