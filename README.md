# OLA#2 : Pure Data & suite de Fibonacci

## À propos

Ce dépôt fait suite au workshop [OLA #2](http://outilslibresalternatifs.org/ola2/) organisé par [OLA (Outils Libres Alternatifs)](http://outilslibresalternatifs.org), sur la production sonore avec le logiciel [Pure Data](https://puredata.info).

Il contient les patchs réalisés à cette occasion, hormis le patch relatif au contrôleur utilisé, celui-ci ayant son propre dépôt (pure-data-korg-nanokontrol-2).

Les abstractions de ce dernier dépôt sont nécéssaires au fonctionnement de l'interface, mais l'essentiel peut être réutilisé sans.

La version de Pure Data utilisée était la 0.45.4.

## Contenu

### Patch principal (instrument.pd)

Ce patch est une tentative de générer des [suites de Fibonacci](https://fr.wikipedia.org/wiki/Suite_de_Fibonacci) et de générer du son sur la base de celles-ci.

### Abstractions

  * adsr.pd : création d'enveloppe simple
  * cmax.pd : permet de laisser passer un certain nombre de messages
  * fibonacci.pd : génère une suite de Fibonacci à partir de deux nombres
  * note-korgi.pd : génération de note via osc~
  * phasor-korgi.pd : génération de note via phasor~
  * quartet.pd : permet de jouer quatre notes données avec un délai donné
  * tiers.pd : donnes deux valeurs intermédiaire entre deux nombres n1 et n2

## Licence

[GNU GPL](https://gnu.org/licenses/gpl.html)
