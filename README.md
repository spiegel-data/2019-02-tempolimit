# Unfallhäufigkeit und Unfallschwere auf Autobahnabschnitten mit/ohne Tempolimit

*Patrick Stotz, SPIEGEL ONLINE; Februar 2019*

# Übersicht
In diesem Repository sind die Daten und Berechnung zum Artikel ["Tempolimit verhindert bis zu 140 Todesfälle im Jahr"](http://www.spiegel.de/artikel/a-1254504.html), erschienen bei SPIEGEL ONLINE am 23.02.2019, dokumentiert.

# Ergebnisse
Unter [diesem Link](https://spiegel-data.github.io/2019-02-tempolimit/01_Auswertung.html) finden Sie alle Analyseergebnisse, die uns als Grundlage für den Artikel gedient haben.

# Reproduzierbarkeit
Die Verarbeitung und Analyse der Daten wurde in der Programmiersprache R durchgeführt.
Der Analyseprozess kann durch Ausführen der Notebooks `00_Datenaufbereitung.Rmd` und `01_Auswertung.Rmd` nachvollzogen werden.

Die eigentliche Analyse findet dabei in  `01_Auswertung.Rmd` statt. Sämtliche hierfür notwendige Daten sind bereits im Verzeichnis  `data` hinterlegt.

Die Ausführung von `00_Datenaufbereitung.Rmd` ist optional. Hierdruch werden die verwendeten Rohdaten erneut von der ursprünglichen Quelle heruntergeladen, aufbereitet (Verarbeitungszeit ca. 20 Minuten) und im Ordner `data/processed` abgelegt. Die dort bereits mitgelieferten Daten werden hierdurch überschreiben. 

Folgende Packages und Versionen wurden in der Analyse verwendet:

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
