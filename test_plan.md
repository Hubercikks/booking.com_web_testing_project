# Test Plan – Booking.com Search Engine

## 1. Wstęp

Głównym celem działań testowych jest dostarczenie interesariuszom informacji o jakości testowanego produktu.

Niniejszy dokument zawiera kluczowe informacje dotyczące procesu testowania, w tym zakres testów, typy testów oraz komponenty objęte weryfikacją.

---

## 2. Zakres testów

### Realizowane typy testów:

* Testy funkcjonalne
* Testy wydajnościowe

### Testy poza zakresem:

* Testy jednostkowe (realizowane przez developerów)
* Testy automatyczne – brak budżetu na automatyzację

---

## 3. Przedmiot testów

Przedmiotem testów jest komponent wyszukiwarki dostępny na stronie głównej serwisu Booking.com.

Wyszukiwarka umożliwia użytkownikowi wyszukiwanie obiektów noclegowych na podstawie:

* lokalizacji
* dat pobytu
* liczby osób
* filtrów (np. cena, ocena, udogodnienia)

---

## 4. Kryteria zaliczenia / niezaliczenia

### Kryteria zaliczenia:

* Minimum 95% przypadków testowych zakończonych statusem **PASS**
* Brak błędów krytycznych (Critical/Blocker)
* Czas odpowiedzi serwera nie przekracza 700 ms

### Kryteria niezaliczenia:

* Występowanie błędów krytycznych
* Niespełnienie wymagań funkcjonalnych
* Czas odpowiedzi przekracza 700 ms

---

## 5. Kryteria wejścia / wyjścia

### Kryteria wejścia:

* Zakończona implementacja wyszukiwarki
* Dostępne i skonfigurowane środowisko testowe
* Dostęp do maszyny testowej

### Kryteria wyjścia:

* Wszystkie testy zostały wykonane
* Brak błędów krytycznych
* Wyniki testów zostały udokumentowane
* Znane defekty zostały zaakceptowane

---

## 6. Wymagania / funkcjonalności

* Dokumentacja projektowa
* User stories
* Scenariusze testowe

---

## 7. Środowisko testowe

* System: Windows 11 Pro
* Przeglądarki:

  * Firefox
  * Edge
  * Opera
  * Safari
* Łącze internetowe: 300 Mb/s
* Serwer testowy

---

## 8. Harmonogram testów

### Testy funkcjonalne:

* Analiza wymagań i user stories – 1 dzień
* Wykonanie przypadków testowych – 1–2 dni
* Retesty i weryfikacja poprawek – 1 dzień

### Testy wydajnościowe:

* Pomiar średniego czasu odpowiedzi
* Weryfikacja maksymalnego obciążenia systemu

---

## 9. Raport z testów

* Lista wykonanych przypadków testowych wraz ze statusami
* Wyniki testów wydajnościowych
* Podsumowanie testów

---

## 10. Narzędzia

* TestRail
* Jira
* JMeter
* BrowserStack

---

## 11. Zarządzanie defektami

Wszystkie wykryte błędy są raportowane w systemie Jira.

Każdy defekt zawiera:

* priorytet
* przypisaną osobę (developer)
* opis problemu
* komponent

### Proces:

1. Zgłoszenie błędu
2. Naprawa przez developera
3. Retest
4. Zamknięcie zgłoszenia

---

## 12. Role i odpowiedzialności

| Osoba           | Rola                               |
| --------------- | ---------------------------------- |
| Jan Kowalski    | Projektowanie przypadków testowych |
| XYZ             | Weryfikacja user story             |
| Hubert Nieśpiał | Wykonywanie testów                 |

---

## 13. Ryzyka

* Niestabilność środowiska testowego
* Zmiany w wymaganiach
* Ograniczony czas testów
* Zależności od backendu

---
