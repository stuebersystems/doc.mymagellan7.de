# Was ist neu

## LEGENDE

Abkürzung | Bedeutung
----------|----------
FIX       | Korrektur bestehender Funktionalität
NEW       | Neue Funktionalität

## Version 7.1.21 (04.12.2020)

### MYMAGELLAN

* CHANGE: Filteransicht `Fächer`/`Schüler`: Spaltenposition und Gruppierungen bleiben bei Datensatzwechsel innerhalb der Ansicht erhalten (nicht bei Ansichtswechsel). Bei der Ansicht `Schüler` gibt es noch die Besonderheit, dass die Spalte `Kurs` immer die erste Spalte ist.
* CHANGE    | Änderung des Ablaufs, Verarbeitung oder Bedienung

## Version 7.1.10 (05.05.2020)

* FIX: Anzeige der Inhalte der Verzeichnisfelder unter `Schüler > Zeugnisdaten korrgiert`
  * CHANGE: Die Anzeige der `Beurteilungsarten` unter `Fächer` ist angepasst worden. Statt des Drop-Downfeldes, sind jetzt Radio-Buttons verwendet worden, die dem Benutzer die gefilterte Darstellung der Liste nach der Beurteilungsart verdeutlichen. Bitte beachten Sie die angepasste Dokumentation unter [https://doc.mymagellan7.stueber.de/noteneingabe/#eingabe-nach-fachern](https://doc.mymagellan7.stueber.de/noteneingabe/#eingabe-nach-fachern)
* CHANGE: Beim Öffnen der Ansicht `Fächer` ist wie bisher die Vorauswahl so getroffen, dass alle Schülerzeilen zum Fach gezeigt werden. In dieser Ansicht ist kein Editieren möglich. Bitte wählen Sie vor der Eingabe der Ergebnisse die gewünschte Beurteilungsart aus.
* FIX: Problem bei der Anzeige der Beurteilungsart in der Ansicht `Fächer` behoben.
* FIX: Problem bei der Eingabe in der Fächeransicht und Anzeige in der Schüleransicht behoben.
* FIX: Anzeige von Füllwerten korrigiert
* FIX: spaltenbezogene Filterkriterien in der Ansicht `Fächer` sichtbar

## Version 7.1.9 (07.04.2020)

* NEW: Neues Format für mym-Dateien (*.mymx). Neu erzeugte mym-Dateien werden als verschlüsselte XML-Dateien gespeichert. Zuvor exportierte Dateien im alten Format können aber weiterhin eingelesen werden
* FIX: In der Ansicht  `Fächer` und  `Schüler` sind die Felder `schriftl.Note1` - `Endnote (gesamt)` beschreibbar.
* FIX: Filter im Bereich
* CHANGE: in der Ansicht `Schüler` und `Fächer` wird die Spalte `Kurs` als erste Spalte eingeblendet, die das Fachkürzel plus die Kursnummer ausgibt.

## Version 7.1.7 (20.03.2020)

* FIX: unter Fächer eingeblendete Personalnummer bleibt auch beim Fachwechsel erhalten
* FIX: Filterung der Klassen in der linken Spalte der Schüleransicht korrigiert
* FIX: Ausgeblendete Spalten werden auch beim Datensatzwechsel beibehalten
* NEW: veränderter Umgang mit Fehlzeiten und der Option "beim Importieren überschreiben"

!!! danger "Achtung"

    Bitte beachten Sie die Abschnitt [Importlogik > Fehlzeiten](https://doc.magellan7.stueber.de/mymagellancenter/importlogik/#fehlzeiten)

* CHANGE: beim ersten Aufruf der Fächeransicht ist standardmäßig die Filter für die Beurteilungsart auf `alle Beurteilungsarten` gestellt
* NEW: In der Ansicht `Schüler` ist in der rechte Fensterhälfte links vor der ersten Spaltenbezeichnung das Symbol zum Aufruf des Untermenüs zum Ein- und Ausblenden von Spalten.

![Symbol zum Ein- und Ausblenden von Spalten verfügbar](/assets/images/changelog/7.1.7.00.png)

## Version 7.1.5 (05.02.2020)

* FIX: Listenfelder unter `Schüler > Zeugnisdaten` sind auswählbar
* Change: Mym7-Datei kann nicht mehrfach geöffnet werden

## Version 7.1.4 (03.02.2020)

* FIX: versehentlich eingetragene Mahnung kann wieder gelöscht werden
* FIX: zuletzt eingetragene Note wird vor dem Datensatzwechsel gespeichert
* FIX: Eingabe von Noten mit oder ohne Tendenz per Tastatur korrigiert
* FIX: Funktion der Vor- und Zurückschaltfläche im Bereich `Schüler` und `Fächer` überarbeitet

## Version 7.1.3 (08.01.2020)

* NEW: Eingabe der Leistungen per Ziffernblock und Pfeiltasten möglich
* FIX: Sortierung von Umlauten korrigiert
* CHANGE: Fachansicht: Die zuletzt gewählte Sortierung wird beim Wechsel zum nächsten Datensatz für die neue Liste wieder ausgeführt
* CHANGE: Schüleransicht: Die zuletzt gewählte Sortierung wird beim Wechsel zum nächsten Datensatz für die neue Liste wieder ausgeführt
* CHANGE: Beim Start einer MyMAGELLAN-Datei wird die Beurteilungsart der Fächeransicht standardmäßig mit der Auswahl `Alle Beurteilungsarten` voreingestellt. 

## Version 7.1.0 (30.10.2019)

* FIX: Problem der unzuverlässigen Darstellung des Reiters `Datenbank` behoben
* FIX: Speichern der Fenstergröße und Fensterposition angepasst
* CHANGE: Layout angepasst
