> :white_check_mark: *Jeśli będziesz mieć problem z rozwiązaniem tego zadania, poproś o pomoc na odpowiednim kanale na Slacku, tj. `s7e01-laravel-first-steps` (dotyczy [mentee](https://devmentor.pl/mentoring/)) lub na ogólnodostępnej i bezpłatnej [społeczności na Discordzie](https://devmentor.pl/discord). Pamiętaj, aby treść Twojego wpisu spełniała [odpowiednie kryteria](https://devmentor.pl/jak-prosic-o-pomoc/).*

&nbsp;

# `#05` Laravel: Pierwsze kroki (1-9)

Przenieś produkty do bazy danych.

Przygotuj migrację, która będzie się składać z kilku etapów:
- utworzenie tabeli `products` (wymyśl poprawne nazwy kolumn): nazwa, opis, cena
- dodanie do tej tabeli kolumny z kategorią produktu (osobna migracja)
- usunięcie jednej, zbędnej kolumny (osobna migracja)

Następnie utwórz model Eloquent i wykorzystaj go na liście produktów oraz na podstronie produktu - użyj [route model binding](https://laravel.com/docs/12.x/routing#route-model-binding), aby nieistniejący produkt automatycznie zwracał `404`.

Na koniec dodaj filtrowanie listy produktów po kategorii przekazywanej w adresie np. `/products?category=narzedzia`. Brak parametru oznacza wyświetlenie wszystkich produktów.

> **Podpowiedź!** Laravel rozpoznaje działania po nazwie migracji i odpowiednio ją uzupełnia:
> - create_ * _table → tworzenie tabeli
> - add_ * _to_ * _table → dodawanie kolumn
> - remove_ * _from_ * _table → usuwanie kolumn

&nbsp;
> :no_entry: *Jeśli nie posiadasz materiałów do tego zadania tj. **Wideo**, znajdziesz je na stronie [laracasts.com](https://laracasts.com/referral/bogolubow)*

> :arrow_left: [*poprzednie zadanie*](./../04) | ~~*następne zadanie*~~ :arrow_right:
