# Wymagania projektu
- Aplikacja będzie zapisywać protokół rozgrywki w pliku JSON.
- Kod będzie pisany w języku Python
- Rozpoznawanie kart będzie opierać sie na podstawowych algorytmach przetwarzania obrazu.
- Aplikacja będzie wyświetlała na żywo obraz z kamerki. Przy każdym graczu będzie pokazany kolor drużyny do jakiej nalezy.
# Wymagania aplikacji
## SilnikBrydzowy
- Będzie to gŁówna klasa programu, łączy ze sobą pozostałe klasy.
## PrzetwarzanieObrazu
- Analizuje klatki nagrania wideo ze stołu brydżowego.
- Wykrywa karty na stole, oraz rozpoznaje kartę i jej kolor.
## RozpoznawanieKomend
- Przetwarza ścieżkę dźwiękową przy użyciu gotowej biblioteki Vosk.
- Rozpoznawanie odpowiednich komend wypowiadanych przez graczy.
## LogikaGry
- Śledzi przebieg licytacji, ustala kontrakt oraz przypisuje zagrywane karty do kolejnych lew i graczy.
- Kontroluje poprawność zagrań
## GenerowanieProtokolu
- Zapisuje pełny przebieg licytacji, rozgrywki, wykrytych błędów i wyniku do pliku JSON.
## InterfejsUzytkownika
- Wyświetla na żywo obraz z kamerki.
- Wyświetla przy każdym graczu kolor drużyny do jakiej należy co ułatwi ich identyfikacje.
- Prezentuje komunikaty o przebiegu rozgrywki oraz wykrytych błędach.
