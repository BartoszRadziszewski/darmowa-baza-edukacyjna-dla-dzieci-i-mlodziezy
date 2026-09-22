# 🎓 Darmowa Baza Edukacyjna dla Dzieci i Młodzieży

> Interaktywny, przejrzysty katalog bezpłatnych stron, aplikacji, bibliotek cyfrowych i materiałów edukacyjnych dla dzieci, młodzieży, rodziców oraz nauczycieli.

🔗 **Wersja online (GitHub Pages):**  
[https://bartoszradziszewski.github.io/darmowa-baza-edukacyjna-dla-dzieci-i-mlodziezy/](https://bartoszradziszewski.github.io/darmowa-baza-edukacyjna-dla-dzieci-i-mlodziezy/)

---

## 🌟 Funkcje katalogu

- 🔍 **Wyszukiwarka na żywo:** Przeszukiwanie bazy po nazwie, opisie, tematyce lub słowach kluczowych.
- 🎯 **Filtrowanie według wieku:**
  - **3–7 lat** (Przedszkole i edukacja wczesnoszkolna)
  - **8–12 lat** (Szkoła podstawowa)
  - **12+ lat** (Młodzież i szkoła średnia)
  - **Nauczyciele i rodzice** (Gotowe scenariusze, higiena cyfrowa, recenzje bezpieczeństwa)
- 📚 **Filtrowanie według przedmiotów:**
  - Programowanie i technologie
  - Nauki ścisłe i przyroda
  - Matematyka
  - Książki, czytanie i biblioteki
  - Języki obce i polski
  - Sztuka, muzyka i szachy
  - Gry logiczne i wiedza ogólna
  - Materiały dla edukatorów
- 🌐 **Oznaczenia językowe:** Każda pozycja oznaczona jest dedykowaną flagą językową (`[PL]`, `[EN]`, `[PL/EN]`, `[DE]`, `[FR]`, `[UA]`, `[Wielojęzyczny]`).
- ⚡ **Brak zbędnych zależności:** Czysty HTML, CSS i JavaScript – działa błyskawicznie na każdym urządzeniu.

---

## 🚀 Uruchomienie lokalne

Projekt nie wymaga instalacji żadnych pakietów ani serwerów:

1. Sklonuj repozytorium:
   ```bash
   git clone https://github.com/BartoszRadziszewski/darmowa-baza-edukacyjna-dla-dzieci-i-mlodziezy.git
   ```
2. Otwórz plik `index.html` w dowolnej przeglądarce internetowej.

---

## 🤝 Jak dodać nowy serwis (Kontrybucje)

Chętnie przyjmujemy propozycje nowych, wartościowych i bezpłatnych źródeł edukacyjnych!

1. Zrób **Fork** tego repozytorium.
2. W pliku `index.html` znajdź tablicę `resources` wewnątrz znacznika `<script>`.
3. Dodaj nową pozycję w formacie:
   ```javascript
   {
     name: "Nazwa Serwisu",
     age: "8-12", // "3-7" | "8-12" | "12+" | "Nauczyciele"
     cat: "Przyroda", // Programowanie | Przyroda | Matematyka | Czytanie | Języki | Sztuka | Ogólne | Materiały
     lang: "PL", // PL | EN | PL/EN | DE | FR | UA | Wielojęzyczny
     desc: "Krótki, 1-2 zdaniowy opis wartości edukacyjnej.",
     url: "https://adres-strony.pl"
   }
   ```
4. Otwórz **Pull Request**.

---

## 📜 Licencja

Projekt udostępniany na licencji **MIT** (zobacz plik [LICENSE](LICENSE)).
