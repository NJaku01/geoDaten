# geoDaten
Auf der Online-Karte sieht man die Standorte von Senseboxen in Münster. Als Projekt haben wir über den Zeitraum vom Montag den 22.10 bis zum Dienstag den 23.10 selber Sensebox Daten gesammelt  Wenn man über eine Sensebox mit der Maus herüberfährt sieht man auf der rechten Seite einen Temperaturgraph. Dieser zeigt den Temperaturverlauf vom 22.10 alle 2 Stunden. Außerdem sieht man den jeweiligen  Namen der Station eingeblendet.

Die Darstellungen wurden mit den D3 angefertigt, dies hat Folgenden Vor- und Nachteile zu Mapbox:

Vorteile:

•	Die Daten können mit Graphen versehen werden und es können Graphen zu Punkten dargestellt. Mithilfe von Mapbox können nicht einfach Graphen dargestellt werden.

•	Die Möglichkeiten sind deutlich größer als mit Mapbox. Über Mapbox hat man eine festgeschriebene API und kann nur vorgegeben Formen darstellen, in D3 hat man durch die SVGs die Möglichkeit ganz eigene Sachen darzustellen. Des Weiteren können ganz eigene Skalierungen festgelegt werden.

Nachteile:

•	Die dargestellten SVG Elemente sind nicht interaktiv, also ist es zum Beispiel nicht möglich in die Karten zu zoomen. Des Weiteren ist es nicht möglich sich die Koordinaten auszugeben und es ist auch teilweise sehr schwierig  eigene Elemente zu erstellen in Mapbox hat man viele vorgefertigte Elemente

•	Die Daten werden veröffentlicht und jeder kann sie einsehen durch die HTML Datei. Falls man genaue Daten nicht freigeben will sondern nur einen Trend zeigen will, kann D3 nicht verwendet werden
