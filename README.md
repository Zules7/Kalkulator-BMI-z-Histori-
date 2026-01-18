# Kalkulator BMI z Historią

## 1. Wprowadzenie

**Kalkulator BMI z Historią** to aplikacja użytkowa służąca do obliczania wskaźnika masy ciała (BMI – *Body Mass Index*) na podstawie danych wprowadzonych przez użytkownika, takich jak **waga**, **wzrost**, **wiek** oraz **płeć**. Dodatkową i kluczową funkcjonalnością aplikacji jest **zapisywanie wyników BMI w czasie** oraz ich **wizualizacja na wykresie**, co pozwala użytkownikowi monitorować zmiany swojej masy ciała i kondycji zdrowotnej.

Aplikacja jest skierowana do:
- osób dbających o zdrowie i sylwetkę,
- użytkowników monitorujących postępy diety lub treningów,
- uczniów i studentów jako projekt edukacyjny,
- wszystkich, którzy chcą w prosty sposób analizować swoje BMI w czasie.

---

## 2. Cel aplikacji

Celem aplikacji jest:
- umożliwienie **szybkiego i poprawnego obliczenia BMI**,
- **interpretacja wyniku BMI** zgodnie z obowiązującymi normami,
- **zapisywanie historii pomiarów** dla jednego użytkownika,
- **graficzna prezentacja zmian BMI w czasie**,
- zwiększenie świadomości zdrowotnej użytkownika.

---

## 3. Zakres funkcjonalny aplikacji

Poniżej przedstawiono **pełną listę wymagań funkcjonalnych**, czyli szczegółowy opis tego, **co aplikacja ma robić**.

---

## 4. Wymagania funkcjonalne

### 4.1. Wprowadzanie danych użytkownika

Aplikacja musi umożliwiać użytkownikowi wprowadzanie danych niezbędnych do obliczenia BMI.

**Funkcjonalności:**
- możliwość wpisania **wagi ciała** (w kilogramach),
- możliwość wpisania **wzrostu** (w centymetrach lub metrach),
- opcjonalne pole **wiek użytkownika**,
- wybór **płci** (kobieta / mężczyzna / inna – opcjonalnie),
- walidacja danych (brak wartości ujemnych, zerowych, liter zamiast liczb),
- komunikaty o błędach w przypadku niepoprawnych danych.

---

### 4.2. Obliczanie wskaźnika BMI

Aplikacja musi automatycznie obliczać wartość BMI na podstawie wzoru:

> **BMI = waga (kg) / (wzrost (m))²**

**Funkcjonalności:**
- przeliczanie wzrostu z centymetrów na metry,
- dokładne obliczenie BMI z zaokrągleniem do 2 miejsc po przecinku,
- uruchomienie obliczeń po kliknięciu przycisku „Oblicz BMI”,
- możliwość ponownego obliczenia po zmianie danych.

---

### 4.3. Interpretacja wyniku BMI

Aplikacja musi klasyfikować wynik BMI zgodnie z normami WHO.

**Kategorie BMI:**
- poniżej 18,5 – *niedowaga*,
- 18,5 – 24,9 – *waga prawidłowa*,
- 25,0 – 29,9 – *nadwaga*,
- 30,0 i więcej – *otyłość*.

**Funkcjonalności:**
- wyświetlenie kategorii BMI w formie tekstowej,
- zastosowanie kolorów (np. zielony – norma, czerwony – otyłość),
- krótki opis znaczenia wyniku dla zdrowia użytkownika.

---

### 4.4. Zapisywanie historii pomiarów

Aplikacja musi przechowywać historię wszystkich wykonanych pomiarów BMI.

**Funkcjonalności:**
- zapis daty i godziny pomiaru,
- zapis wartości BMI, wagi i wzrostu,
- automatyczne dodanie nowego wpisu po każdym obliczeniu,
- możliwość przechowywania wielu wpisów,
- trwałość danych (np. zapis lokalny lub w bazie danych).

---

### 4.5. Przeglądanie historii BMI

Użytkownik musi mieć możliwość przeglądania zapisanych pomiarów.

**Funkcjonalności:**
- lista wszystkich pomiarów w kolejności chronologicznej,
- możliwość sortowania (od najnowszych / najstarszych),
- wyświetlanie szczegółów pojedynczego wpisu,
- możliwość usunięcia wybranego pomiaru,
- możliwość wyczyszczenia całej historii.

---

### 4.6. Wizualizacja danych – wykres BMI w czasie

Aplikacja musi prezentować historię BMI w formie wykresu.

**Funkcjonalności:**
- wykres liniowy BMI w funkcji czasu,
- oś X – data pomiaru, oś Y – wartość BMI,
- automatyczna aktualizacja wykresu po dodaniu nowego pomiaru,
- możliwość przybliżania i oddalania wykresu,
- czytelna legenda i opisy osi.

---

### 4.7. Obsługa wielu użytkowników (opcjonalnie)

Aplikacja może umożliwiać korzystanie z niej przez więcej niż jednego użytkownika.

**Funkcjonalności (opcjonalne):**
- tworzenie profili użytkowników,
- oddzielna historia BMI dla każdego profilu,
- wybór aktywnego użytkownika.

---

### 4.8. Interfejs użytkownika

Aplikacja musi posiadać prosty i intuicyjny interfejs.

**Funkcjonalności:**
- czytelne formularze danych,
- wyraźne przyciski akcji,
- responsywny układ (różne rozmiary ekranów),
- estetyczne użycie kolorów i nagłówków,
- komunikaty informacyjne i ostrzegawcze.

---

## 5. Podsumowanie

Kalkulator BMI z Historią to funkcjonalna aplikacja umożliwiająca nie tylko jednorazowe obliczenie wskaźnika BMI, ale przede wszystkim **długoterminowe monitorowanie zmian masy ciała**. Dzięki zapisywaniu danych i ich wizualizacji użytkownik otrzymuje narzędzie wspierające dbanie o zdrowie, analizę postępów oraz podejmowanie świadomych decyzji dotyczących stylu życia.

Dokumentacja ta stanowi kompletny opis wymagań funkcjonalnych aplikacji i może być podstawą do jej implementacji, testowania oraz dalszego rozwoju.

