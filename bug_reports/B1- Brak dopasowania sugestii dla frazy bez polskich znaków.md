Bug ID: BR_AUTOCOMPLETE_001

Title: Brak dopasowania sugestii dla frazy bez polskich znaków (Gdan → Gdańsk)

Environment:

System: Windows 11 Pro
Przeglądarka: Firefox / Edge / Opera / Safari
Aplikacja: wyszukiwarka (inspirowana Booking.com)

Preconditions:

Użytkownik znajduje się na stronie głównej aplikacji
Pole wyszukiwania „Dokąd się wybierasz?” jest widoczne i aktywne

Steps to reproduce:

1. Kliknij w pole „Dokąd się wybierasz?”
2. Wpisz frazę: `Gdan`

Expected result:

System wyświetla listę sugestii w dropdownie
Wśród sugestii znajduje się „Gdańsk”
System uwzględnia dopasowanie frazy bez polskich znaków (np. „Gdan” → „Gdańsk”)

Actual result:

System nie wyświetla sugestii zawierającej „Gdańsk”
Wyświetlane sugestie są niepowiązane z wprowadzoną frazą lub brak sugestii

Severity: Medium
Priority: High

Frequency: 100% (problem występuje przy każdej próbie)

Additional notes:

Problem może wynikać z braku obsługi znaków diakrytycznych (ł, ń, ą itd.)
Możliwy brak implementacji mechanizmu fuzzy search lub normalizacji tekstu

Status: Open

