
> [!WARNING]
> Work in progress!

# Plan nauki

## 🧠 Matematyka 1 **test**

<hr>
## Własności funkcji

| Tematy                       | Stan               | Uwagi |
|:-----------------------------|:------------------:|:------|
| Składanie funkcji            | ✅ Zrobione	     |Po prostu wstawianie pod x pierwszej funkcji całą drugą funkcję|
| Różnowarotościowość          | ✅ Zrobione	     |f(x1)=/=f(x2) => f(x1)-f(x2)=/=0|
| Funkcje odwrotne             | ⬜ Do zrobienia     |       |
| Bijekcja                     | ⬜ Do zrobienia     |       |
| Surrekcja                    | ⬜ Do zrobienia     |       |
| Zbiór przekształceń          | ✅ Zrobione	     |zbiór funkcji zamieniających zbiór X w zbiór Y (czyli w sumie każda funkcja)|
<hr>
## Struktury Algebraiczne

| Tematy                       | Stan               | Uwagi |
|:-----------------------------|:------------------:|:------|
| Zbiory                              | ⬜ Do zrobienia     |       |
| Grupa i grupa abelowa               | ✅ Zrobione	        |⚠️Ważne!|
| Ciało/Pierścienie                   | ✅ Zrobione	        |⚠️Ważne!|
| Dzielenie wielomianów w pierścieniu | ⬜ Do zrobienia     |⚠️Ważne!|
<hr>
## Permutacje

| Tematy                       | Stan               | Uwagi |
|:-----------------------------|:------------------:|:------|
| Liczba inwersji              | ⬜ Do zrobienia     |       |
<hr>
## Liczby zespolone

| Tematy                       | Stan               | Uwagi |
|:-----------------------------|:------------------:|:------|
| Wstęp do liczb zespolonych (co to jest?)       | ⬜ Do zrobienia     |       |
| Powtórzyć funkcje trygonometryczne i pi        | ⬜ Do zrobienia     |       |
| Powtórzyć równanie elipsy i równanie hiperboli | ⬜ Do zrobienia     |       |
| Płaszczyzny zespolone                          | ⬜ Do zrobienia     |⚠️Ważne!|
<hr>
## ✅ Macierze ✅

| Tematy                       | Stan               | Uwagi |
|:-----------------------------|:------------------:|:------|
| Działania na macierzach (+, mnożenie, transpozycja) | ✅ Zrobione	        |Raczej proste rzeczy (odejmowanie to dodawanie z minusem)|
| Macierz odwrotna                                    | ✅ Zrobione	        |Metoda Gausa, bierzemy macierz jednostkową i przekształcamy|
| Wyznaczniki macierzy                                | ✅ Zrobione    	    |       |
| Rząd macierzy                                       | ✅ Zrobione	        |Wymiar największej macierzy jednostkowej, lub też liczba schodków w macierzy schodkowej|
| Powtórzyć symbol newtona                            | ✅ Zrobione	        |n po k = n!/k!·(n-k)!|
| Grupa                                               | ⬜ Do zrobienia     |       |
<hr>
## Układy równań

| Tematy                       | Stan               | Uwagi |
|:-----------------------------|:------------------:|:------|
| Metoda Gaussa                | ⬜ Do zrobienia     |       |
| Metoda Macierzowa            | ✅ Zrobione	     |       |
| Metoda Wyznacznikowa         | ⬜ Do zrobienia     |       |
| Wzory Crammera               | ⬜ Do zrobienia     |       |
<hr>

# Notatki

## Struktury Algebraiczne

Aksjomaty grupy (X, #):
- działanie musi być wewnętrzne
- łączność (a#b)#c=a#(b#c)
- element neutralny e#x=x#e=x
- element odwrotny y#x=x#y=e
- jeśli dodatkowo działanie jest przemienne to grupa jest abelowa a#b=b#a

Aksjomaty pierścienia (X,⊕,⊙):
- Zbiór jest grupą abelową
- drugie działanie musi być łączne (a⊙b)⊙c=a⊙(b⊙c)
- drugie działanie musi być rozdzielne względem pierwszego (a⊕b)⊙c=(a⊙c)⊕(b⊙c)
- element neutralny pierwszego działania to zero
- drugie działanie nie musi mieć elementu neutralnego, ale jeśli go ma to jest przemienny z 1

## Macierze

Macierze to tak jakby współczynniki układów równań w tabeli dwuwymiarowej

Działania na macierzach - dodawać i odejmować można tylko wtedy kiedy mają takie same wymiary, mnożenie jest możliwe wtedy kiedy liczba kolumn (najpierw wiersze potem kolumny) pierwszej macierzy jest równa liczbie wierszy drugiej i wtedy 1 element nowej macierzy to 1 wiersz pierwszej macierzy razy 1 kolumna drugiej a drugi element pierwszy wiersz pierwszej razy druga kolumna drugiej itd.

Przekształcanie macierzy - macierze przekształcają się tak jak układy równań, można mnożyć wiersze przez liczby (jak dwie strony równania) i dodawać je do siebie

Wyznacznik macierzy (rozwinięcie Laplace'a) WYZNACZNIKI PISZEMY Z "||" ZAMIAST "[]" - Jeśli mamy macierz 2x2 to wystarczy równanie a11*a22-a12*a21, jeśli jednak mamy 3x3 to bierzemy "pod kątem"liczby najpierw od lewej do prawej mnożymy wszystkie ze sobą na skos i dodajemy a potem to samo ale z minusem, jeśli jednak mamy powyżej 3x3 musimy użyć rozwinięcia Laplace'a, względem wiersza skreślamy wiersz który nam jest niepotrzebny dodajemy każdą liczbę tego wiersza pomnożoną przez -1 do potęgi i+j (nr wiersza i kolumny w których stoi liczba) i razy wyznacznik macierzy która zostaje po wykreśleniu wiersza i kolumny w których stoi Liczba

Wyznacznik macierzy schodkowej = pomnożone przez siebie liczby z przekątnej

## Układy równań (z macierzami)

M (macierz rozszerzona = [A|B] , n liczba niewiadomych

Jeśli: 
- rzA=/=rzM - układ sprzeczny
- rzA=rzM=n - układ oznaczony (jedno rozwiązanie)
- rzA=rzM<n - układ nieoznaczony (nieskończenie wiele rozwiązań) (liczba parametrów rzA-n)

Metoda Macierzowa - (można stosować gdy macierz kwadratowa i detA=/=0) X=A^-1·B


# Zadania z pracy domowej

| Nr zadania                   | Stan               | Uwagi |
|:-----------------------------|:------------------:|:------|
| 2  str 33 | ✅ Zrobione      	  |       |
| 3  str 33 | ⬜ Do zrobienia     |       |
| 4  str 33 | ⬜ Do zrobienia     |       |
| 8  str 47 | ⬜ Do zrobienia     |       |
| 9  str 47 | ⬜ Do zrobienia     |       |
| 10 str 47 | ⬜ Do zrobienia     |       |
| 11 str 48 | ⬜ Do zrobienia     |       |
| 14 str 48 | ⬜ Do zrobienia     |       |
| 13 str 49 | ⬜ Do zrobienia     |       |
| 14 str 49 | ⬜ Do zrobienia     |       |
| 15 str 49 | ⬜ Do zrobienia     |       |
| 16 str 49 | ⬜ Do zrobienia     |       |
| 18 str 50 | ⬜ Do zrobienia     |       |
| 3  str 74 | ✅ Zrobione      	  |       |
| 4  str 74 | ⬜ Do zrobienia     |Nie wiem jak zrobić|
| 9  str 78 | ⚠️Błędy             |Nie wiem jak zrobić podpunkty b i c|
| 11 str 78 | ✅ Zrobione      	  |       |
| 12 str 79 | ✅ Zrobione      	  |       |
| 15 str 79 | ✅ Zrobione      	  |       |
| 18 str 82 | ✅ Zrobione      	  |       |
| 23 str 84 | ✅ Zrobione      	  |       |
| 4  str 94 | ✅ Zrobione      	  |       |
| 5  str 94 | ⚠️Błędy             |dlaczego przykład d jest sprzeczny?|
| 1  str 93 | ✅ Zrobione      	  |       |
| 17 str 81 | ✅ Zrobione      	  |       |


<!-- Tak się robi komentarz
Wieloliniowy
-->