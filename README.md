# Klasyfikator naiwny Bayesa
Projekt samorozwojowy w Pythonie dla lepszego zapoznania się z metodą klasyfikacji Bayesa. Dane do projektu zaczerpnięte ze strony https://archive.ics.uci.edu/ml/datasets/Glass+Identification. Wykorzystane zostały biblioteki: Pandas, Seaborn, SciPy, NumPy. 

Projekt obejmuje:
1. Zmianę dziedziny dwóch atrybutów z ciągłej na dyskretną (wartości logiczne)
1. Odrzucenie wartości odstających dla modelu
1. Podgląd danych na wykresach
1. Implementację funkcji sprawdzających prawdopodobieństwo przynależności rekordu do klasy na podstawie wartości atrybutów (przyjmujących dodatkowo wektor wzmocnienia wag poszczególnych cech)
1. Implementację funkcji klasyfikującej rekord do konkretnej grupy
1. Badanie wpływu wartości w wektorze wzmocnienia wag na wynik trafności klasyfikacji uzyskanej na zbiorze treningowym
1. Sprawdzenie otrzymanego klasyfikatora na zbiorze walidacyjnym
