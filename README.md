
# Repozytorium Paula Czajkowska

## O mnie
Cześć, nazywam się Paula Czajkowska, jestem początkującym testerem oprogramowania, w tym miejscu chciałbym podzielić się z Tobą moim doświadczeniem oraz projektami, które miałam dotychczas przyjemność wykonać. 
<center>

![profile](img/profile.jpg)

</center>

## Testowanie
Testowanie oprogramowania jest niezmiennie ważnym elementem procesu wytwarzania oprogramowania. Moje pierwsze kroki w tym kierunku stawiałam dość nieświadomie korzystając z różnych aplikacji, w których miałam okazje znaleźć pewne nieścisłości. Jestem osobą, która lubi poszukać dziury w całym, a jednocześnie skupiam się na detalach. Postanowiłam, że zostanę testerem oprogramowania i moje umiejętności przydadzą się w Twoim zespole.

## Kurs Software Development Academy
Miałam przyjemność uczestniczyć w kursie "Tester oprogramowania" organizowanym przez Software Development Academy. Przez 105 godzin zajęć oraz wiele godzin poświęconych na pracę samodzielną zdobyłam wiedzę z następujących tematów wymienionych poniżej.
<center>

[Certyfikat szkolenia](https://app.diplomasafe.com/pl-PL/diploma/d5113e3c90933e5bcff2bbb27e50a49617e654521)

</center>

Sprawnie będę poruszała się także w projektach zwinnych, dzięki zajęciom wprowadzających do metodyki Scrum:

<center>

![profile](img/scrum_certificate.png)

</center>

## Git oraz HTTP
W czasie kursu nauczyłam się nie tylko testować, ale rozwijałam swoje umiejętności w wielu kierunkach między innymi:

* Nauczyłam się pracy z Narzędziem GIT (oraz Gitlab)

* Nauczyłam się podstaw REST API oraz narzędzi sieciowych, dzięki czemu w przyszłej pracy, będę mógła testować back-end przy pomocy odpowiednich narzędzi.

## Certyfikat ISTQB
W czasie kursu przygotowywaliśmy się do egzaminu ISTQB Foundation Level, do którego obecnie się przygotowuję i planuję w najbliższym czasie podejść.



## Zadania, które wykonywałem w czasie kursu:
<center>

* Wprowadzenie do testowania | Cykl życia oprogramowania, Podstawy testowania, typy testów, Proces testowy, Podstawy techniczne
* Techniki projektowania testów | Techniki czarnoskrzynkowe, baiłoskrzynkowe, praca z dokumentacją testową
* Testowanie w oparciu o ryzyko | Identyfikacja i analiza ryzyka, ryzyko projektowe i produktowe, zarządzanie ryzykiem.
* Testowanie wspierane narzędziami | Repozytoria wymagań testów i incydentów, Narzędzia wspomagające debugowanie oraz raportowanie testów. Zajęcia praktyczne.
* Bazy danych | Model organizacji bazy danych, komunikacja między użytkownikiem lub aplikacją o relacyjną bazą danych za pomocą języka SQL.
* Automatyzacja testów | Wprowadzenie do programowania, Podstawy Seleniuum WebDriver. Testowanie w metodyce BDD.
* Projekt podsumowujący | Projekt do przetestowania polegający na zastosowaniu zdobytej wiedzy w praktyce.
* Przygotowanie do ISTQB Level Foundation | Podstawy testowania, Testowanie w cyklu życia oprogramowania, Statyczne techniki testowania, Techniki projektowania testów, zarządzanie testowaniem, narzędzia wspierające testowanie.

</center>

## Moje projekty

* [Przypadki Testowe](Przypadki Testowe)  dla strony [Connectors Poland](https://connectors.pl/)

* [Przypadki Testowe](Przypadki Testowe) dla strony [Electro](https://www.electro.pl/lp,k-2651-nawet-400-zl-taniej?clickId=146538)

* [Zapytania](Zapytania) REST API w ramach ćwiczeń.

* [Testy Automatyczne](Testy Automatyczne) nagrane przy pomocy narzędzia Selenium IDE.

* [Testy Automatyczne](Testy_automatyczne), z wykorzystaniem Selenium WebDriver.

## Moje przykładowe scenariusze testowe

<center>

Użycie dla strony avans.pl 

Przykład 1
1. Użytkownik klika przycisk Konto
2. Użytkownik klika przycisk Zarejestruj się
3. Użytkownik podaje dane do rejestracji
4. Dane zostają zaakceptowane przez system
5. Użytkownik zaznacza pole wymagane z akceptacją regulaminu	
6. Użytkownik zaznacza zgodę na otrzymanie newslettera
7. System przyjmuje prośbę rejestracji i wysyła użytkownikowi link potwierdzający rejestrację na adres mailowy, wymagający otwarcia w skrzynce mailowej
8. Użytkownik potwierdza rejestrację wchodząc na link w wiadomości
9. Konto zostaje utworzone poprawnie

Ścieżki alernatywne
4a. system odrzuca proponowany login, ponieważ taki już istnieje.
4a3. Powrót do kroku 3
4b. System odrzuca proponowane hasło, brak znaku specjalnego
4b3. Powrót do kroku 3
5a. Użytkownik nie zaznacza akceptacji regulaminu
5a3. Powrót do kroku 3
6a Użytkownik nie wyraża zgody na otrzymanie newslettera
6b. Użytkownik nie otrzymuje newslettera
8a. Użytkownik nie otrzymuje wiadomości z linkiem potwierdzającym rejestrację konta
8a3. Powrót do kroku 3

Przykład 2
1. Użytkownik klika przycisk Konto
2. Użytkownik wybiera opcję zaloguj się podając login i hasło
3. System stwierdza poprawność danych
4. Użytkownik zostaje zalogowany do systemu
Ścieżki alternatywne
3a System odrzuca podane dane
3a2. Powrót do kroku 2

1. The user clicks the Account button
2. The user clicks the Register button
3. The user provides data for registration
4. The data is accepted by the system
5. The user selects the required field to accept the regulations
6. The user agrees to receive the newsletter
7. The system accepts the registration request and sends the user a link confirming registration to the e-mail address, which must be opened in the e-mail box
8. The user confirms the registration by clicking on the link in the message
9. The account is created correctly

1. Kliknij przycisk Konto
2. Kliknij przycisk Zarejestruj się
3. Podaj dane do rejestracji
4. Dane zostają zaakceptowane przez system
5. Zaznacz pole wymagane z akceptacją regulaminu
6. System przyjmuje prośbę rejestracji i wysyła wiadomość powitalną na podany adres mailowy.
7. Konto zostaje utworzone poprawnie	

- Go on electro.pl
- Click the Account button
- Click the Register button
- Provide your registration details
- The data is accepted by the system
- Check the field required to accept the regulations
- The system accepts the registration request and sends a welcome message to the e-mail address provided.
- The account is created correctly

- Go on electro.pl
- Scroll to the bottom of the page and find the section from the newsletter
- Enter your e-mail address in the address box and confirm
- You will receive confirmation of subscription to the newsletter to the e-mail address provided
- You joined the newsletter with success


Moje opisy przykładowych błędów z gier:
0:30 Slow loadind textures:
-Textures are loading slowly, after environment is loaded the player is standing outside, a building appears later and the player is suddenly standing inside this building.

0:56 Stepping into window sills
- The player is walking along the wall, walking into window sills textures.

1:13 Disappearing hand when choosing a plastic bottle
- The player is choosing a plastic bottle from selection bar. The player's hand overlaps the textures of the knee.

1:26 
Door textures are overlapping the player.
- The player are opening the door outside standing in the front of them, door textures are overlapping the player when are opening. 

1:55  Closed door on the corpse
- the corpse lying in the passage, you can lock the door on it and the corpse are visible through the door.

1:58  Blinking glass
- The glass on the right side of door is blinking.

2:15  Vanishing ceiling
- The player is walking into the room and ceiling in this place vanish when you look above.

2:24  Weapon visible through the head
-The player crawls, when he rotating the view around, the textures of the weapon overlapping the player's head.

2:36 Disappearing item in the interface
- The player choose hands item, this item is not visable on interface. After choosing, item aappears in window, but looks diffrent than wearing item.

2:52  Disappearing textures of items when aiming snipe.
- When the player is aim snipe, the textures of items armor are disappear.


</center>

## Screeny z przykładowych zadań testowych
[https://gitlab.com/PaulaCzjk/test/-/blob/5f186ded7e776a84780d89b9b0adf13f69123177/postman.png
](url)
[](url)
## Zainteresowania
Testowanie to nie wszystko, w wolnym czasie jestem zaciętym graczem w grach typu Moba, MMO RPG i Single Player.

<center>

![mtb](img/mtb.jpg)

</center>

## Kontakt

Skontaktuj się ze mną mailowo: paula.czajkowska.p@gmail.com

Linkedin: [Paula Czajkowska](https://www.linkedin.com/in/paula-czajkowska-a4709b116/)
