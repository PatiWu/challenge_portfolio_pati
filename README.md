## Spis treści
1. [Task 1](https://github.com/PatiWu/challenge_portfolio_pati/edit/main/README.md#task-1)

   1.1 [Subtask 1](https://github.com/PatiWu/challenge_portfolio_pati/edit/main/README.md#subtask-1)

   1.2 [Subtask 3](https://github.com/PatiWu/challenge_portfolio_pati/edit/main/README.md#subtask-3)

   1.3 [Subtask 4](https://github.com/PatiWu/challenge_portfolio_pati/edit/main/README.md#subtask-4)
     * [Przeznaczenie aplikacji](https://github.com/PatiWu/challenge_portfolio_pati/edit/main/README.md#przeznaczenie-aplikacji)
     * [Funkcjonalności](https://github.com/PatiWu/challenge_portfolio_pati/edit/main/README.md#funkcjonalno%C5%9Bci)
     * [Interface](https://github.com/PatiWu/challenge_portfolio_pati/edit/main/README.md#interface-nie-jest-przyjazny)
     * [Błędy](https://github.com/PatiWu/challenge_portfolio_pati/edit/main/README.md#b%C5%82%C4%99dy-i-propozycje-ich-poprawienia) 
2. [Task 2](https://github.com/PatiWu/challenge_portfolio_pati/edit/main/README.md#subtask-3-1)
 
   2.1 [Subtask 1](https://github.com/PatiWu/challenge_portfolio_pati/edit/main/README.md#subtask-1-1)
   
   2.2 [Subtask 2](https://github.com/PatiWu/challenge_portfolio_pati/edit/main/README.md#subtask-2)
   
   2.3 [Subtask 3](https://github.com/PatiWu/challenge_portfolio_pati/edit/main/README.md#subtask-3-1)

# Task 1
## Subtask 1
![](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d2/Eo_circle_deep-purple_number-8.svg/240px-Eo_circle_deep-purple_number-8.svg.png)

## Subtask 3
#### *Hej! Jestem Pati :blush:. Od dłuższego czasu przymierzam się do sprawdzenia swoich sił w branży IT :muscle:. Na fali noworocznych zmian wraz z wyczuwalnym powiewem sukcesu pojawiła się możliwość uczestnictwa w projekcie Zostań Testerem Manualnym - nie mogłam przejść obojętnie obok :sunglasses:. Zależy mi przede wszystkim na poznaniu specyfiki pracy testerki poprzez działanie a co za tym idzie - zapełnienie swojego portfolio projektami. Moim celem jest dostanie się na staż :moneybag:. Bardzo zachęcające okazało się również wsparcie Mentorek w trakcie kursu - wierzę, że otrzymamy dużo ciekawych i przydatnych informacji. Liczę również na dobrą zabawę - a co! Nie samą pracą człowiek żyje :smiling_imp:.*

## Subtask 4
#### Przeznaczenie aplikacji:
* po pierwsze: przeznaczenia nie oszukasz :rocket:
* po drugie: aplikacja jest stworzona dla łowców talentów piłki nożnej. Daje dostęp do przydatnych informacji na temat piłkarza takich jak wzrost, waga, wiek itd oraz najważniejszych osiągnięć. Łowca może również pobrać gotowy raport zawierający niezbędne informacje.
#### Funkcjonalności:
* przeglądanie wskaźników i informacji piłkarza
* dodawanie i edycja gracza
* dodawanie i edycja meczu
* pobieranie raportów
 
 *Wnioski: aplikacja nie jest intuicyjna. Informacje w sekcji dotyczącej gracza są chaotycznie ułożone, powinny być pogrupowane. W każdym z pól można wpisać dowolne wartości, np. w polu, w którym powinny znajdować się wartości liczbowe można wpisać np. litery.*
#### Interface **nie jest przyjazny:**
* brak przejrzystości
* brakuje grafiki, ikonek, które przyspieszyłyby poruszanie się w aplikacji
* brakuje menu
* brak sekcji kontakt i pomoc
#### Aplikacja nie jest intuicyjna:
Z poziomu głównego menu nie ma możliwości kliknięcia w informacje o danym meczu czy danej drużynie. Nie ma możliwości również dodania nowego gracza. Raporty dostępne są dopiero po kliknięciu w danego gracza. Jeżeli użytkownik aplikacji lubi chaos to poczuje się jak ryba w wodzie :grin:.
#### Błędy i propozycje ich poprawienia:
*Testowane na Windows, przeglądarka Chrome, tryb incognito*
* [Gracze](https://scouts-test.futbolkolektyw.pl/pl/players)
  * brak możliwości dodania gracza - można jedynie edytować już istniejących
  * adres mailowy można wpisać cokolwiek (bez @)
  
  **powienien od razu wyskakiwać komunikat, że wpisano błędny adres**
  * imię i nazwisko można wpisać nieskończenie wiele znaków i rownież znaki inne niż litery 
 
  **blokada innych znaków niż litery**
  **ograniczenie do 30 liter**
  * telefon - można wpisać litery
  
  **narzucony format (kierunkowy kraju plus 6 cyfrowy format)**
  * waga i wzrost - można wpisać wartości ekstremanie duże oraz ujemne
 
  **waga - narzucony przedział (np. od 40 - 100) - miara narzucona - kg**
  **blokada możliwości wpisania wartości ujemnych**
  **wzrost - narzucony przedział (np. 130 - 210) - miara narzucona - cm**
  **blokada możliwości wpisania wartości ujemnych**
  * data urodzenia - można dodać datę z przyszłości oraz bardzo przeszłą
 
  **zablokowoana możliwość dodania daty przyszłej**
  * główna pozycja i pozycja alternatywna - można wpisywać inne znaki niż litery
 
  **wybór z listy rozwijanej**
  * województwo Dolnoślaskie - literówka
 
  **powinno być DolnoślAskie na DolnoślĄskie**
  * link do Youtube - można wpisać cokolwiek, można dodawać nieskończenie wiele pól jednocześnie nie dodając do nich treści
 
  **narzucony format http, można dodać kolejne pole jak wcześniejsze zostało uzupełnione**
  * dodaj język - można wpisać cokolwiek, można dodawać nieskończenie wiele pól jednocześnie nie dodając do nich treści
 
  **wybór z listy rozwijanej, można dodać kolejne pole jak wcześniejsze zostało uzupełnione**
  * po błędnym uzupełnieniu pola (np. błędny adres mailowy) profil gracza nie zapisuje się - brak informacji, które z pól należy poprawić
 
  **zaznaczenie na czerwono pola, które zostało błędnie uzupełnione**
  * każdy może dokonać edycji gracza

  **edycja gracza tylko przez login, z którego został utworzony**
  * po zapisaniu gracza pojawia się informacja wraz ze wskaźnikiem upływającego czasu - niepotrzebnie
  
  **informacja o prawidłowym zapisaniu gracza znika po 4 sekundach**
  
* [Mecze](https://scouts-test.futbolkolektyw.pl/pl/players/6026b48956c79737b3f3c624/matches)
  * drużyna i drużyna przeciwna - można wpisać cokolwiek
  **wybór z listy rozwijanej**

  * zdobyte gole - brak max wartości
  * data - można dodać datę z przyszłości oraz bardzo przeszłą

  **zablokowana możliwość dodania daty przyszłej**
  * czas gry - można wpisać wartości ujemne

  **powinien być narzucony przedział, wpisany miernik (min.)**
  * numer - można wpisać wartości ujemne

  **powinien być narzucony przedział**
  * web match i general - wpisane w j. angielskim

  **powinna być spójność i wpisane w języku polskim**
 
* Pozostałe:
  * [dodawanie raportu do gracza](https://scouts-test.futbolkolektyw.pl/pl/players/6026b48956c79737b3f3c624/reports/add?matchId=6311f33d806291c83d9fd815) - nie działa
  * mimo iż nie mam zarejestrowanego konta mailowego w aplikacji to po kliknięciu w przypomnij hasło i wpisaniu maila wyskoczyło info, że hasło zostało wysłane - nie  otrzymałam żadnej wiadomości
  * informacja o błędnie wpisanym adresie lub haśle wyświetla się w j.angielskim
  * [link strony w stopce](https://scouts-test.futbolkolektyw.pl/players/6026b48956c79737b3f3c624/reports/63c6e2a64cff3d0bdc152cbc/edit) - nie działa poprawnie
   [Page not found 404](https://scouts-test.futbolkolektyw.pl/pl/players/6026b48956c79737b3f3c624/reports/63c6e2a64cff3d0bdc152cbc/www.futbolkolektyw.pl)
  
  * [link adresu mailowego w stopce](https://scouts-test.futbolkolektyw.pl/players/6026b48956c79737b3f3c624/reports/63c6e2a64cff3d0bdc152cbc/edit) nie działa poprawnie

# Task 2
## Subtask 1 
*link do google drive [[KLIK]](https://docs.google.com/spreadsheets/d/1rYWi2ovXgqDEjZbVmLByuVoVv052FImbfB35RqXidO8/edit#gid=2029615675)*

## Subtask 2 
*link do google drive [[KLIK]](https://docs.google.com/spreadsheets/d/1AFZGiyogVNeWSZlCWNzrDye-GW_Lkj2HaxZn2uQszTo/edit#gid=0)*

## Subtask 3
#### Na co komu test case'y?
*Bo człowiek lubi komplikować sobie życie :grin:. A tak serio to wspaniały pomysł na spędzenie wolnego czasu :tropical_drink:. A oprócz tego test case'y to udokumentowane różne możliwości obsłużenia poszczególnych funkcjonalności danej aplikacji. Są zbiorem informacji na temat danej aplikacji a ich przeprowadzenie daje odpowiedź czy dane funkcjonalności działają zgodnie z przyjętymi założeniami.*


