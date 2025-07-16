# Interaktywny Dashboard Sprzedaży w Excelu

![Podgląd Dashboardu](https://github.com/MarSnop99/-Excel-Sales-Dashboard/blob/main/Dashboard%20Screenshot.png?raw=true)

## 1. Cel Biznesowy Projektu
Celem projektu było przekształcenie surowego zbioru danych sprzedażowych w pełni interaktywne narzędzie analityczne. Dashboard pozwala na szybką identyfikację trendów, analizę wyników regionalnych oraz znalezienie najlepiej sprzedających się produktów.

## 2. Użyte Technologie
*   **MS Excel**
*   **Power Query:** do procesów ETL (Extract, Transform, Load) - czyszczenia, łączenia i transformacji danych.
*   **Tabele Przestawne:** jako silnik obliczeniowy dla raportu.
*   **Wykresy Przestawne i Fragmentatory:** do stworzenia warstwy wizualnej i interaktywnej.

## 3. Proces Realizacji
1.  **ETL:** Dane zostały zaimportowane do Power Query, gdzie przeszły proces czyszczenia (usunięcie błędów, standaryzacja formatów) i transformacji (dodanie kolumn z nazwą miesiąca, dniem tygodnia).
2.  **Analiza:** Oczyszczone dane posłużyły do stworzenia serii tabel przestawnych, agregujących dane według kluczowych wymiarów (czas, region, produkt).
3.  **Wizualizacja:** Na podstawie tabel przestawnych zbudowano interaktywny dashboard z dynamicznymi filtrami (fragmentatorami), które kontrolują wszystkie wykresy jednocześnie.

## 4. Główne Wnioski z Analizy
*   Najwyższa sprzedaż jest notowana w regionach wschodnim i zachodnim.
*   Najwyższa sprzedaż jest notowana pod koniec roku. 
*   Najgorszym miesiącem jest luty, a najgorszym dniem tygodnia czwartek.

## 5. Jak Używać
Pobierz plik `.xlsx`, włącz edycję i korzystaj z fragmentatorów na arkuszu "Dashboard" do dynamicznego filtrowania danych.
