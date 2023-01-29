# symulacja-orzel-reszka-dynamic
Projekt dotyczy losowego przestawiania żetonów ułożonych na prostokątnej planszy o wymiarach m wierzy i n kolumny  wg. zadanego algorytmu  


![image](https://user-images.githubusercontent.com/31622223/215337368-f05ed77b-b0f9-497d-89e3-7bcf0a642208.png)

Rys. 1: Początkowe ustawienie żetonów


Algorytm przestawiania żetonów:

a.Początkowe ustawienie żetonów jest takie, że w pierwszych dwóch kolumnach
znajdują się żetony żółte (1, orzeł, itp.), a w pozostałych żetony niebieskie (0, reszka);
b.Dla każdego żetonu losowana jest liczba z przedziału od 1 do 4;

c.Kolejno każdy z żetonów zamieniany jest miejscami z żetonem znajdującym się w tym
samym wierszu, w kolumnie o numerze wylosowanym w punkcie b.

d.Po dokonaniu zamiany wszystkich żetonów operacje b-c są powtarzane jeszcze
czterokrotnie.
