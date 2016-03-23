Map Your Hood!
==============================

Map your hood! ist eine **[OpenStreetMap](http://openstreetmap.org/) Mapping Party im Bezirk Gries**, in dem Restaurants und Cafes in die OpenStreetMap eingetragen werden sollen. OpenStreetMap ist die Wikipedia für geographische Informationen, und steht somit allen frei zu nutzen, bearbeiten und teilen.

- Datum: 25. März 2016
- Ort: Büro der Nachbarschaften, Gries, Graz
- Veranstaltung: [Open Knowledge Austria](http://okfn.at/2016/03/15/map-your-hood/)

Der Inhalt steht, soweit nicht explizit anders erwähnt, unter der [Creative Commons Namensnennung 4.0 Lizenz](https://creativecommons.org/licenses/by/4.0/).

## ABLAUF

| Timetable     | Agenda       |
|---------------|--------------|
| 14:00 - 14:30 | Einführung OpenStreetMap |
| 14:30 - 15:00 | Vorbereitung Daten sammeln |
| 15:00 - 16:00 | Daten sammeln (Gelände) |
| 16:00 - 16:15 | Pause |
| 16:15 - 16:45 | Einführung JOSM Editor |
| 16:45 - 18:00 | Daten in OpenStreetMap eintragen|
| 18:00         | ENDE |

### 1. Einführung OpenStreetMap

1. Willkommen
2. Was machen wir heute?
3. Was ist OpenStreetMap?
4. Was ist eine Mapping Party?
5. Fragen

**Quellen**
- [OpenStreetMap Austria](https://wiki.openstreetmap.org/wiki/WikiProject_Austria)
- [OpenStreetMap Graz](https://wiki.openstreetmap.org/wiki/Graz)
- [OpenStreetMap](openstreetmap.org)
- [Mapping Party](http://wiki.openstreetmap.org/wiki/Mapping_parties)

### 2. Vorbereitung Daten sammeln
Die Gruppen auf das Sammeln der Daten im Gelände draußen vorbereiten.

1. Gruppen bilden: 2-3 Personen (wenn geht eine erfahrene) + Kamera
2. Aussuchen des Gebietes und nehmen des Field Paper Sets
3. Welche Informationen sollen gesammelt werden: Restaurants und Cafes in Gries
	- Adresse
	- Name
	- Rollstuhltauglichkeit
	- Raucherbereich
	- Küche → Kebab
	- Öffnungszeiten: Fotos von Schild. Aufpassen, dass es scharf ist!
4. Field Papers erklären
5. Ablauf wiederholen
	- Punkt auf Karte ansehen
	- Daten eintragen in Liste
	- Foto von Front machen, eventuell von Öffnungszeiten-Schild. Fotos so machen, dass von Schild auf Front also auf Adresse rückgeschlossen werden kann.
	- Daten in Karte eintragen
	- Nächster Punkt und wieder von vorne
6. Checken, ob alles passt:
	- Ablauf
	- Field Paper und Gebiets-Grenzen
	- Camera
	- Stift
	- Notizzettel und Tabelle

**Beachten**
Wenn hier strukturiert vorgegangen wird, geht nachher beim Eintragen der Daten in die OpenStreetMap alles ganz einfach.

**[Field Papers](http://fieldpapers.org/)**
- [Griesplatz]()
- [Griesgasse]()
- [Rösslmühlgasse]()
- [Idlhofgasse/Elisabethinnengasse]()
- [Annenstraße Ost]()
- [Annenstraße Ost-Mitte]()
- [Annenstraße West-Mitte]()
- [Annenstraße West]()
- [Belgiergasse]()

### 3. Daten sammeln
In den Gruppen draußen in Gries herum gehen und die Daten sammeln.

### 4. Pause
15min Pause

### 5. Einführung JOSM Editor
Kurze Einführung in [JOSM](https://josm.openstreetmap.de/), dem OpenStreetMap Editor. Damit können ganz einfach am Laptop/PC die Daten aus der OpenStreetMap bearbeitet werden.

1. JOSM [runterladen]() und installieren
2. Account bei [OpenStreetMap]() anlegen
3. JOSM starten
4. JOSM erklären
5. OpenStreetMap Account authentifizieren
6. [Plugin für Öffnungszeiten](https://wiki.openstreetmap.org/wiki/JOSM/Plugins/OpeningHoursEditor) installieren
7. Daten zu Kartenausschnitt runter laden
8. Daten sichern
9. Daten ansehen

Eine Liste mit allen Map-Features die es in der OpenStreetMap gibt, ist [hier](https://wiki.openstreetmap.org/wiki/Map_Features) zu finden.

**Beachten**
- Text in ganz normaler Sprache, also mit Umlauten und Scharfen-ß.

### 6. Daten in OpenStreetMap eintragen
Die selbst-gesammelten Daten werden in JOSM eingetragen und am Ende in die OpenStreetMap hochgeladen.

1. Einen Datenpunkt nach dem anderen eintragen und sichern
2. Alle Daten hochladen
3. Daten ansehen

**Attribute der Daten**
- [name](https://wiki.openstreetmap.org/wiki/DE:Key:name) Name des Restaurants, Cafes, Shops, etc.
- [addr:street](https://wiki.openstreetmap.org/wiki/DE:Key:addr)
- [addr:housenumber](https://wiki.openstreetmap.org/wiki/DE:Key:addr)
- [addr:city](https://wiki.openstreetmap.org/wiki/DE:Key:addr)
- [opening_hours](https://wiki.openstreetmap.org/wiki/DE:Key:opening_hours) → eintragen mit JOSM Plugin
- [amenity](https://wiki.openstreetmap.org/wiki/DE:Map_Features#Nutzung.2FEinrichtung) → individuell nachsehen
- [cuisine](https://wiki.openstreetmap.org/wiki/DE:Key:cuisine) → wird verwendet, um die Art der angebotenen Speisen in Restaurants oder Cafes zu beschreiben. Es sollte nur der Hauptart der angebotenen Speisen getaggt werden
- [smoking](http://wiki.openstreetmap.org/wiki/DE:Key:smoking)
	- yes → im ganzen Restaurant erlaubt
	- no → im ganzen Restaurant verboten ohne Ausnahmen
	- separated → Rauchen ist erlaubt in einem entsprechend bezeichneten Raum oder Bereich, entweder in zwei unterschiedlichen Bereichen im selben Raum, oder in verschiedenen Räumen ohne wirksame Trennung, beispielsweise wenn die Türe nicht sofort geschlossen wird, nachdem sie benutzt wurde. 
	- isolated → Rauchen ist in einem Raum verboten, in einem anderen erlaubt, und die beiden Räume sind wirksam voneinander getrennt (z.B. durch geschlossene Wände und eine Tür, die stets nur so lange geöffnet wird, wie es zum Passieren notwendig ist). 
- [wheelchair](https://wiki.openstreetmap.org/wiki/DE:Key:wheelchair)
	- yes → nur verwenden, wenn für ganze Räumlichkeit sichergestellt
		- Eingang: stufenlos
		- Räume: stufenlos erreichbar
		- Toiletten (falls vorhanden): rollstuhlgerechte Kabine (ein Rollstuhl passt neben das WC)
	- limited
		- Eingang: Stufe ist kleiner als 7 cm ('eine Hand breit')
		- Räume: die wichtigsten sind stufenlos erreichbar
		- Toiletten (falls vorhanden): nicht rollstuhlgerecht
	- no
		- Eingang: Stufe ist höher als 7 cm ('eine Hand breit')
		- Räume: die wichtigsten sind nicht stufenlos erreichbar
		- Toiletten (falls vorhanden): nicht rollstuhlgerecht
- [source](https://wiki.openstreetmap.org/wiki/DE:Key:source):name=survey
- [source](https://wiki.openstreetmap.org/wiki/DE:Key:source):addr=survey



