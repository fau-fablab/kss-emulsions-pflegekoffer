KSS-Emulsions-Pflegekoffer
==========================

Anleitung des [FAU FabLab](https://fablab.fau.de) für den KSS-Emulsions-Pflegekoffer (Kühlschmierstoff der Drehbank).

Inhalt
------

- KSS-Werte messen: pH-Wert, Nitrat, Nitrit, Wasserhärte mit Grenzwerten
- KSS-Konzentration mit dem Refraktometer messen und korrigieren
- Dokumentation im Wartungsplan der Drehbank

Download
--------

Die neueste Version aus [GitHub](https://github.com/fau-fablab/kss-emulsions-pflegekoffer) ist als PDF abrufbar:

- [Anleitung](https://brain.fablab.fau.de/build/kss-emulsions-pflegekoffer/Anleitung_Pflegekoffer.pdf)

Auschecken und bauen
--------------------

```bash
git clone --recursive git@github.com:fau-fablab/kss-emulsions-pflegekoffer.git
cd kss-emulsions-pflegekoffer
make
```

Die PDFs landen in `output/`. Layout, Kopf- und Fußzeile und das Logo des FAU FabLab (mit
FAU-Schriftzug) kommen aus dem Untermodul [fablab-document](https://github.com/fau-fablab/fablab-document),
das Logo wiederum aus dessen Untermodul [logo](https://github.com/fau-fablab/logo). Bei einem bestehenden
Klon die Untermodule mit `git submodule update --init --recursive` laden.

Technische Details zum Buildserver: [fau-fablab/buildserver](https://github.com/fau-fablab/buildserver)

[![Build Status](https://brain.fablab.fau.de/build/kss-emulsions-pflegekoffer/status.svg)](https://brain.fablab.fau.de/build/kss-emulsions-pflegekoffer/)
[![TODOs](https://brain.fablab.fau.de/build/kss-emulsions-pflegekoffer/status-todos.svg)](https://brain.fablab.fau.de/build/kss-emulsions-pflegekoffer/)

Lizenz
------

[![Lizenz: CC BY-SA 3.0](https://licensebuttons.net/l/by-sa/3.0/de/88x31.png)</br>CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/)
