# Kopiowanie ofert Allegro

Prywatne narzędzie desktopowe (Windows) do kopiowania ofert między dwoma
kontami Allegro należącymi do tego samego właściciela.

## Cel działania
Aplikacja pobiera oferty z konta źródłowego i wystawia ich kopie na koncie
docelowym. Nie jest udostępniana innym użytkownikom i nie przenosi ofert
poza serwis Allegro.

## Wykorzystywane uprawnienia API
- allegro:api:sale:offers:read – odczyt ofert konta źródłowego
- allegro:api:sale:offers:write – tworzenie ofert na koncie docelowym
- allegro:api:sale:settings:read / write – cenniki dostaw, warunki zwrotów
  i reklamacji potrzebne do poprawnego wystawienia kopii

## Autoryzacja
OAuth 2.0 Device Flow, zgoda wyrażana osobno na każdym z kont.

## Kontakt
Zgłoszenia przez zakładkę Issues tego repozytorium.
