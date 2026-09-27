# WorkshopFlow 360

Interaktywny model obsługi niezależnego warsztatu samochodowego. Pokazuje pełny przebieg pracy: rezerwację, diagnozę, kosztorys, zgodę klienta, części, naprawę, kontrolę jakości, fakturę i wydanie auta.

## W środku

- strona procesu i studium przypadku,
- portal ról oraz widok klienta,
- dane demonstracyjne dla zespołu, stanowisk i KPI,
- dokumentacja zasad prywatności.

## Jak zobaczyć projekt

Otwórz `index.html` w przeglądarce.

## Działająca prezentacja

[Otwórz WorkshopFlow 360](https://lukaszst-cz.github.io/workshopflow-360/)

## Szybki podgląd

- [Widok klienta](https://lukaszst-cz.github.io/workshopflow-360/portal/?role=client)
- [Widok kierownika](https://lukaszst-cz.github.io/workshopflow-360/portal/?role=manager)
- [Case study](https://lukaszst-cz.github.io/workshopflow-360/case-study.html)

Projekt jest częścią głównego [portfolio operacyjnego](https://github.com/lukaszst-cz/operations-office-portfolio).


## Powiązany projekt

Auto Naprawa KSeF Demo rozwija wątek dokumentów, faktur i obsługi klienta wokół warsztatu.

https://github.com/lukaszst-cz/auto-naprawa-ksef-demo


## Zakres demonstracji

WorkshopFlow 360 pokazuje proces operacyjny warsztatu i podział informacji między rolami. Publiczny portal:
- korzysta wyłącznie z danych syntetycznych;
- nie ma prawdziwego logowania ani serwerowego RBAC;
- zapisuje lokalnie tylko wybór roli i demonstracyjną decyzję klienta;
- nie wysyła danych do zewnętrznej bazy.

Auto Naprawa KSeF Demo rozwija ten sam kontekst o stronę klienta, faktury i demonstracyjny przebieg KSeF.

## Kontrola jakości

GitHub Actions sprawdza składnię JavaScript, lokalne linki i assety, obecność wszystkich 9 ról, komunikat o publicznej symulacji oraz podstawowe etykiety dostępności portalu.
