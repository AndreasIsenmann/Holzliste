# Holzliste

Für welchen Zweck ist dieses Excel-Dokument gedacht? Nach dem trockenen Sommer 2019 musste möchglichst schnell das angefallene Kamalitätsholz aus dem Wald gebracht werden. Dies hat dazu geführt, dass mehrere Waldbesitzer ihr Holz auf einem gemeinsamen Polter zur Abfuhr bereit gestellt haben. Nach der Abrechnung muss nun der Erlös aus einem solchen Polter auf die beteiligten Waldbesitzer aufgeteilt werden.

Was dabei ist genau das Problem?

Holz auf dem Polter wird durch die Waldbesitzer mit Rinde gemessen, bei der Abrechnung hingegen wird die Rinde abgezogen. Zudem werden die einzelnen Stämme in unterschiedliche Qualität eingeteilt und dementsprechend auch unterschiedlich abgerechnet.

Wie funktioniert die Excel-Tabelle ganz grob?

Im ersten Schritt wird erfasst, welche Stämme auf dem Polter aufgenommen wurden. In zweiten Schritt wird dann die Sägeliste zu diesem Polter eingegeben und schlussendlich wird im dritten Schritt die Abrechnung vom Sägewerk eingegeben.

Die hinterlegten Formeln vom Excel-Dokument erledigen eine automatische Zuordnung der ursprünglich auf dem Polter erfassten Stämme vom Polter und ermöglichen somit eine einfache Abrechnung unter den beteiligten Holzbesitzern.

## Mögliche Probleme

Sind auf dem Polter mehrere oder gar viele Stämme mit gleicher Länge und Durchmesser jedoch mit unterschiedlicher Qualität, kann eine automatische Zuordnung nicht erfolgen.

Grundsätzlich kann es bei der Zuordnung zu Fehler kommen, die sich schlussendlich auch auf die Abrechnung auswirken können.

## Allgemeiner Hinweis zur Bearbeitung

Bei der Bearbeitung bitte folgende Hinweise beachten:

* Das Dokument enthält Makros. Damit die Auswertung erfolgen kann, müssen daher Makros zugelassen werden. Ok, dies stellt ein Sicherheitsrisiko dar, aber ohne geht es leider nicht. ;-)
* Alle Eingabefelder sind mit gelber Farbe hinterlegt
* Es können bis zu 50 Stämme auf einem Polter abgerechnet werden

## Anleitung Schritt für Schritt

### Tabellenblatt "Holzliste"

Für jeden Stamm auf dem Polter muss der Besitzer, die Holzart, sowie die Länge in Meter und der Mittendurchmesser in Zentimeter erfasst werden.

Folgende Holzarten werden hierbei unterstützt:

* Tanne
* Fichte
* Douglasie
* Buche
* Esche
* Kiefer
* Eiche
* Lärche

Für andere Holzarten kann der Rindenabzug nicht ermittelt werden und daher ist eine Abrechnung nicht möglich.

### Tabellenblatt "Sägeliste"

Auf diesem Tabellenblatt muss für jeder Stamm der Sägeliste erfasst werden. Dabei wird wieder die Holzart, die HKS-Länge in Zentimeter sowie der Mittendurchmesser in Millimeter erfasst. Zusätzlich muss für jeden Stamm noch die Güte und Klasse erfasst werden.

### Tabellenblatt "Gutschrift"

Auf diesem Tabellenblatt wird die Gutschrift vom Sägewerk eingegeben. Die Gutschrift erfolgt in der Regel zusammengefasst für jede Holzart, Klasse und Güte.

Außerdem können auf diesem Tabellenblatt auch noch verschiedene Abzüge bei der Abrechnung erfasst werden, die dann auf die abzurechnenden Festmeter umgelegt werden.

### Tabellenblatt "Abrechnung"

Auf diesem Tabellenblatt kann mit der Schaltfläche "Abrechnung aktualisieren" die Aufteilung der Stämme vom Polter vorgenommen und die Abrechnung für die beteiligten Besitzer erstellt werden.

Fertig.

#### Lizenz GPL-3.0

Das Dokument wird unter der GNU General Public License v3.0 zur Verfügung gestellt.

(c) 2020 Andreas Isenmann
