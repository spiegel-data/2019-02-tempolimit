# Unfallhäufigkeit und Unfallschwere auf Autobahnabschnitten mit/ohne Tempolimit

*Patrick Stotz, SPIEGEL ONLINE; Februar 2019*

# Übersicht
In diesem Repository sind die Daten und Berechnung zum Artikel "[ARTIKELTITEL EINFÜGEN](LINK EINFÜGEN)", erschienen am XX.02.2019 im SPIEGEL/bei SPIEGEL ONLINE, dokumentiert.

# Ergebnisse
Unter [diesem Link](LINK EINFÜGEN) finden Sie alle Analyseergebnisse, die uns als Grundlage für den Artikel gedient haben.

# Reproduzierbarkeit
Die Verarbeitung und Analyse der Daten wurde in der Programmiersprache R durchgeführt.
Der Analyseprozess kann durch Ausführen der Notebooks `00_Datenaufbereitung.Rmd` und `01_Auswertung.Rmd` nachvollzogen werden.

Die Ausführung von `00_Datenaufbereitung.Rmd` ist dabei optional. Hier werden Rohdaten heruntergeladen und vorverarbeitet (Verarbeitungszeit ca. 20 Minuten).

Alternativ kann auch direkt die eigentliche Analyse in `01_Auswertung.Rmd` ausgeführt werden. Sämtliche hierfür notwendige Daten sind im Repository hinterlegt.

Folgende Packages und Versionen wurden verwendet:

* R version 3.5.1
* tidyverse 1.2.1
* sf 0.7-2
* osmdata 0.0.8
* rmapshaper 0.4.1

# Datenquellen
* Geodaten Autobahnnetz: Quelle: OpenStreeMap (OSM), Stand: 18.02.2019. © OpenStreetMap-Mitwirkende.
* Unfalldaten: Quelle: [Unfallatlas der statistischen Ämter des Bundes und der Länder 2017](https://unfallatlas.statistikportal.de/_opendata.html).
* Verkehrsdichte: [automatische Verkehrszählung der bast 2017](https://www.bast.de/BASt_2017/DE/Verkehrstechnik/Fachthemen/v2-verkehrszaehlung/Aktuell/zaehl_aktuell_node.html).

# Kontakt
Bei Fragen wenden Sie sich bitte an patrick.stotz(at)spiegel.de oder an [@SPIEGEL_Data](https://twitter.com/SPIEGEL_Data).