# High Power RGB Lamp Driver

## Language Notice  
**[ENG]** Sorry, this repository is currently only available in Polish.  
**[PL]** Wszystkie najważniejsze informacje znajdują się w dokumentacji `.pdf`.

Dokumentacja zawiera:
- Opis funkcjonalny projektu  
- Uzasadnienie doboru komponentów  
- Schemat blokowy i ideowy  
- Widoki 3D płytki oraz rzuty warstw  
- Materiały i źródła wykorzystane podczas realizacji projektu  

---

## Opis projektu

**Sterownik RGB wysokiej mocy** to układ oparty na mikrokontrolerze **STM32F051K6T6**, umożliwiający precyzyjne sterowanie jasnością i kolorem lamp RGB o mocy do **20 W**. 

Wykorzystanie **interfejsu dotykowego** (przycisk + slider) pozwala na intuicyjną i szybką obsługę.

Projekt oferuje trzy tryby pracy (ON/OFF/AUTO) oraz graficzny interfejs z użyciem **wyświetlacza E-PAPER**.

Układ jest zaprojektowany pod działanie z **Vin typowym dla akumulatorów Li-Ion** (od 2.7 do 4 V), dzięki wykorzystaniu przetwornic buck-boost oraz boost.

Czterowarstwową płytkę zaprojektowano w programie **Altium Designer** z myślą o komforcie użytkownika podczas korzystania.

---

## Pliki

Najważniejsze pliki i dokumentacja znajdują się w repozytorium. Zachęcam do zapoznania się z dokumentacją PDF.
