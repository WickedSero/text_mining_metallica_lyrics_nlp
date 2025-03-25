# Analiza tekstów piosenek Metalliki - Projekt Text Mining

## Opis projektu

Ten projekt został stworzony jako zaliczenie z przedmiotu Text Mining. Celem jest analiza tekstów piosenek zespołu Metallica przy użyciu technik przetwarzania języka naturalnego i analizy danych.

## Główne funkcjonalności

### Wczytywanie i przetwarzanie danych

- Importowanie tekstów piosenek z pliku CSV
- Czyszczenie i normalizacja tekstów
- Lematyzacja słów i usuwanie stop words


### Analiza częstości słów

- Zliczanie unikalnych słów w tekstach piosenek
- Tworzenie listy najczęściej używanych słów
- Generowanie chmury słów (word cloud)


### Analiza sentymentu

- Wykorzystanie modelu VADER do analizy sentymentu tekstów
- Obliczanie wartości sentymentu (negatywny, neutralny, pozytywny, złożony)


### Wizualizacja danych

- Tworzenie wykresów słupkowych dla najczęściej używanych słów
- Generowanie chmury słów


## Użyte biblioteki

- pandas
- nltk
- sklearn
- matplotlib
- seaborn
- WordCloud
- vaderSentiment


## Główne etapy analizy

1. Wczytanie danych i usunięcie zbędnych kolumn
2. Czyszczenie i normalizacja tekstów piosenek
3. Ekstrakcja unikalnych słów i zliczanie ich częstości
4. Wizualizacja najczęściej używanych słów
5. Analiza sentymentu tekstów piosenek
6. Zapis wyników do plików CSV

Ten kod stanowi kompleksowe narzędzie do analizy tekstów piosenek, umożliwiając zarówno analizę częstości słów, jak i badanie sentymentu utworów.
