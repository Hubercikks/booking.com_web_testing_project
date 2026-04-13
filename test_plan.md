. Wstęp

Głównym celem działań testowych jest dostarczenie interesariuszom informacji o jakości testowanego produktu.

W przygotowanym dokumencie zostały zebrane kluczowe informacje na temat działań testowych. Zostały wyszczególnione wszystkie komponenty oprogramowania, które zostaną poddane weryfikacji, typy testów jakie zostaną przeprowadzone

2. Zakres Testów

Realizowane typy testów:
Jednostkowe 
Funkcjonalne
Wydajnościowe
Typy testów, które nie zostaną przeprowadzone:
Testy automatyczne - ze względu braku wystarczającego budżetu na etap związany z testowaniem
3. Przedmioty testów

Komponentem poddawanym testom jest wyszukiwarka ze strony głównej Booking.com z uwzględnieniem całej logiki filtrowania po odpowiednich polach

4. Kryteria zaliczenia / niezaliczenia testów

Wykonanie zaprojektowanych przypadków testowych
Czas odpowiedzi serwera nie przekracza 700ms
5. Kryteria wejścia / wyjścia

Kryteria wejścia
Zakończona jest faza implementacji wyszukiwarki
Działające i skonfigurowane środowisko testowe
Dostęp do działającej i skonfigurowanej maszyny wirtualnej
2. Kryteria wyjścia

Wszystkie przypadki testowe zostały zakończone pomyślnie
Komponent spełnia wszystkie założenia i wymagania z załączonej dokumentacji
6. Lista wymagań / funkcjonalności do przetestowania

Załączenie wszystkich dokumentacji, user story, scenariuszy itp.

7. Środowisko testowe

Testowy serwer
System Windows 11 Pro
Przeglądarki biorące udział w testach: Firefox, Edge, Opera, Safari
Łącze internetowe o prędkości 300mp/s
8. Harmonogram testów

Przeprowadzenie testów funkcjonalnych:
Weryfikacja funkcjonalności w oparciu o user story - 3h
Wykonanie wcześniej zaprojektowanych przypadków testowych - 1h
Weryfikacja warstwy backendowej
2. Przeprowadzenie testów wydajnościowych:

Weryfikacja średniego czasu odpowiedzi
Weryfikacja maksymalnej ilości requestów przy jakiej wyszukiwarka działa stabilnie
9. Raport z testów

Lista zrealizowanych przypadków testowych wraz ze statusami
Pomiary z testów wydajnościowych
Inne raporty z testów
10. Lista narzędzi

Jmeter
TestRail
Jira
Browserstack
11. Zarządzanie incydentami, błędami

W procesie testowym każdy wykryty incydent powinien być odpowiednio zaraportowany do systemu Jira.

Uwzględniając przy tym priorytet błędu, osobę przypisaną(developera), komponent którego dotyczy problem

Zgodnie z przyjętym flow przez naszą organizację taki problem powinien zostać naprawiony przez developera i trafić do retestów.

12. Role i odpowiedzialności

Jan Kowalski - Projektowanie przypadków testowych

XYZ - Weryfikacja user story

Hubert Nieśpiał - Wykonywanie przypadków testowych
