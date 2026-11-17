> :white_check_mark: *Jeśli będziesz mieć problem z rozwiązaniem tego zadania, poproś o pomoc na odpowiednim kanale na Slacku, tj. `s7e01-laravel-first-steps` (dotyczy [mentee](https://devmentor.pl/mentoring/)) lub na ogólnodostępnej i bezpłatnej [społeczności na Discordzie](https://devmentor.pl/discord). Pamiętaj, aby treść Twojego wpisu spełniała [odpowiednie kryteria](https://devmentor.pl/jak-prosic-o-pomoc/).*

&nbsp;

# `#02` Laravel: Pierwsze kroki (1-9)

Utwórz layout, który będzie zawierał nagłówek oraz stopkę.

- **nagłówek** - składa się z loga oraz menu
- **stopka** - menu, o tej samej zawartości co w nagłówku

Layout przygotuj jako [komponent Blade](https://laravel.com/docs/12.x/blade#components), a treść podstron wstawiaj przez `$slot`. Tytuł strony przekazuj jako `prop` z wartością domyślną.

Menu należy generować przy pomocy [pętli](https://laravel.com/docs/12.x/blade#loops) i odpowiedniej struktury danych [przekazanej do widoku](https://laravel.com/docs/12.x/views#passing-data-to-views).

Pamiętaj, aby oznaczyć, która pozycja menu jest aktualnie przeglądana - przygotuj odpowiednie podstrony.

> **Podpowiedź!** Aktualny adres możesz sprawdzić przy pomocy [`request()->is()`](https://laravel.com/docs/12.x/requests#inspecting-the-request-path).

&nbsp;
> :no_entry: *Jeśli nie posiadasz materiałów do tego zadania tj. **Wideo**, znajdziesz je na stronie [laracasts.com](https://laracasts.com/referral/bogolubow)*

> :arrow_left: [*poprzednie zadanie*](./../01) | [*następne zadanie*](./../03) :arrow_right:
