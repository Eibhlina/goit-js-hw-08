# Zadanie — Galeria obrazków

Utwórz galerię z możliwością kliknięcia w jej elementy i przeglądania obrazu w pełnym rozmiarze w oknie modalnym. Zobacz demonstracyjne wideo działania galerii.



Tworzenie galerii to złożone zadanie, które lepiej podzielić na kilka prostszych podzadań, wykonując każde z nich, zbliżasz się do końcowego celu. Ten proces nazywa się dekompozycją zadania.


## 1 - Układ galerii

Logiczne jest zacząć od stworzenia miejsca, do którego będziemy dodawać elementy galerii. W tym celu w kodzie HTML dodaj kontener galerii - nieuporządkowaną listę z klasą gallery.

## 2 - Tablica obrazów

Do stworzenia elementów galerii będziesz potrzebować danych. Dodaj ten tablicę obiektów do swojego pliku JavaScript. Każdy obiekt reprezentuje jeden element galerii.

preview — link do małej wersji obrazu dla karty galerii
original — link do dużej wersji obrazu dla okna modalnego
description — opis tekstowy obrazu, dla atrybutu alt małego obrazu i podpisu dużego obrazu w oknie modalnym.

## 3 - Układ elementów galerii

Masz już kontener, do którego można dodawać elementy galerii, i dane, za pomocą których je stworzyć. Teraz czas wypełnić galerię układem.

Użyj tablicy obiektów images i tego szablonu HTML elementu galerii, a następnie stwórz układ elementów w kodzie JavaScript, a następnie dodaj cały układ do ul.gallery. Nie dodawaj innych tagów HTML poza tymi, które są zawarte w tym szablonie.


* W atrybucie src tagu <img> podaj link do małej wersji obrazu.
* Dla atrybutu alt użyj opisu obrazu.
* Link do dużego obrazu powinien być przechowywany w atrybucie danych source na elemencie <img>, a adres powinien być podany w atrybucie href.
* Zwróć uwagę, że obraz jest opakowany w link, którego atrybut href wskazuje na ścieżkę do pliku z obrazem. Kliknięcie w ten link może spowodować pobranie obrazu na komputer użytkownika. Zablokuj to zachowanie domyślnie.


## 4 - Style

Dodaj stylizację galerii zgodnie z projektem.


## 5 - Delegacja

Nadszedł czas, aby dodać funkcjonalność nasłuchiwania kliknięć na elementach galerii i uzyskiwania linku do dużego obrazu po kliknięciu. Użyj techniki delegacji na ul.gallery. Na razie po kliknięciu na element galerii wyświetl adres do dużego obrazu w konsoli.


## 6 - Podłączenie biblioteki

Biblioteka basicLightbox zapewnia w pełni funkcjonalne okno modalne, które doskonale nadaje się do naszego zadania. Użyj serwisu CDN jsdelivr i dodaj w pliku HTML linki do zminifikowanych plików JS i CSS biblioteki.


## 7 - Okno modalne

Rozszerz swój kod tak, aby po kliknięciu na element galerii otwierało się okno modalne podłączonej biblioteki. Aby dowiedzieć się, jak zainicjować okno modalne w swoim kodzie i jak z niego korzystać, zapoznaj się z dokumentacją i przykładami.


## 8 - Duży obraz

Wykorzystaj swój kod uzyskiwania linku do dużego obrazu, aby zmienić wartość atrybutu src elementu <img> w oknie modalnym przed otwarciem. Użyj gotowego układu okna modalnego z obrazem z przykładów biblioteki basicLightbox.


## 9 - Zamknięcie za pomocą klawiatury

Dodaj funkcjonalność zamykania okna modalnego po naciśnięciu klawisza Escape. Upewnij się, że nasłuchiwanie klawiatury zachodzi tylko wtedy, gdy otwarte jest okno modalne. Biblioteka basicLightbox zawiera metodę do programowego zamykania okna modalnego.
