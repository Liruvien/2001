# 2001

## Opis gry
Gra **2001** to prosta gra liczbowo-losowa.

### Zasady Gry
1. Każdy z graczy zaczyna z liczbą punktów równą 0.
2. W swojej turze gracz rzuca 2 kośćmi do gry (standardowe kości sześciościenne).
3. Suma wyrzuconych oczek jest dodawana do sumarycznej liczby punktów gracza.
4. Począwszy od drugiej tury:
    - Jeśli gracz wyrzuci 7, dzieli swoją liczbę punktów przez 7, odrzucając część ułamkową.
    - Jeśli wyrzuci 11, mnoży aktualną liczbę punktów przez 11.
5. Wygrywa gracz, który jako pierwszy uzyska 2001 punktów.

## Implementacja
- Gra jest zaprojektowana dla dwóch graczy: gracza (użytkownika) oraz komputera.
- Jest to aplikacja konsolowa.
- Po każdej turze wyświetlana jest aktualna liczba punktów obu graczy.
- Gracz wykonuje rzut po naciśnięciu klawisza `Enter`. Komputer wykonuje rzut automatycznie po graczu.
- Gra kończy się, gdy gracz lub komputer osiągnie więcej niż 2001 punktów.

## Modyfikacja: Wybór kości
W celu urozmaicenia gry, dodajemy możliwość wyboru różnych kości.

1. Przed każdym rzutem gracz ma możliwość wyboru dwóch kości z zestawu:
   - D3, D4, D6, D8, D10, D12, D20, D100
2. Gracz może wybrać dwie takie same kości lub dwie różne.
3. Wybór kości odbywa się poprzez wprowadzenie odpowiedniego kodu (np. `D6`, `D12`) dla każdej z kości.
4. Wybór kości dla komputera jest losowy.
5. Reszta zasad pozostaje bez zmian.

## Wymagania
- Python 3.x

## Uruchomienie
1. Skopiuj repozytorium do swojego lokalnego systemu.
2. Aby uruchomić grę konsolową, wykonaj następującą komendę:
   python3 2001.py
