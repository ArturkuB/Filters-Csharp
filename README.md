## Spis treści
* [Ogólne informacje](#ogólne-informacje)
* [Użyte technologie](#użyte-technologie)
* [Prezentacja programu](#prezentacja-programu)

## Ogólne informacje
Program modyfikuje obrazy wykorzystując algorytmy filtrów wyostrzających w oparciu o operator Robertsa, Prewitta, Sobela(poziome i pionowe, operator Laplace’a oraz filtry statystyczne(min, max, median).
<h3>Filtry wyostrzające:</h3>

<img src="https://i.imgur.com/hkQVxdU.png">

(Mechanizm filtracji splotowej obrazu I przy użyciu maski h o rozmiarze 3 × 3. Przemnożone
przez współczynniki maski wartości jasności obrazu zostaną zsumowane i podzielone
przez sumę współczynników maski.)

 <h3>Filtry statystyczne:</h3>
 <b>Filtry statystyczne</b> to nieliniowe przestrzenne filtry, których
działanie jest oparte na kolejności wartości punktów zawartych
w obrębie maski filtru.
<h4>Filtr minimum i maximum:</h4>

W obu przypadkach <b>filtru minimum i maksimum</b> wartość
poszukiwana punktu wymaga ustalenia porządku wartości
punktów z otoczenia zdefiniowanego przez maskę filtru, czyli
posortowania ich względem wartości.<br>
Dla <b>filtru minimum</b> wartością szukaną jest najmniejsza wartość
z posortowanego ciągu:

<img src="https://i.imgur.com/9NKTx3x.png">

gdzie M oznacza rozmiar maski filtru.

Analogicznie dla <b>filtru maksymalnego</b> nową wartością jest
największa wartość po uszeregowaniu otoczenia:

<img src="https://i.imgur.com/1TKoWmj.png">

<h4>Filtr medianowy:</h4>
<b>Filtr medianowy</b>
zgodnie z nazwą po uszeregowaniu wartości punktów z
otoczenia szukaną wartością jest mediana, czyli wartość
środkowa:

<img src="https://i.imgur.com/je2yuBE.png">

	
## Użyte technologie
Projekt został utworzony z wykorzystaniem:
* Język C#
* Visual Studio 2019

## Prezentacja programu
[![IMAGE ALT TEXT](https://img.youtube.com/vi/2Hey_eqS_rA/0.jpg)](https://www.youtube.com/watch?v=2Hey_eqS_rA "Filters")

