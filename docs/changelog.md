# Was ist neu

## Wichtige Hinweise

!!! danger "Achtung"

    **OpenSSL-Schwachstelle**: In unseren Softwareprodukten setzen wir kein OpenSSL ein.

    **Log4Shell-Schwachstelle**: Unsere Software-Produkte ENBREA, DAVINCI, MAGELLAN, CONFIRE SHOWTIME und CONFIRE SHERLOCK sind alle nicht von der Log4Shell-Schwachstelle betroffen, da keines dieser Produkte Java verwendet oder von einer externen Java-Anwendung abhängig ist. Auch unsere öffentlich zugänglichen Dienste (z.B. Ticketsystem, Webseiten) nutzen alle kein Java. Bitte lesen Sie auch unseren [Blogeintrag](https://blog.stueber.de/posts/log4j-desaster).

## LEGENDE

Abkürzung | Bedeutung
----------|----------
FIX       | Korrektur bestehender Funktionalität
NEW       | Neue Funktionalität

## Version 10 (14.02.2023)

* NEW: Die Felder `Bestanden` und `Leistungsart` aus `Schüler > Zeugnis > Leistungen` können mit in eine MyMAGELLAN-Datei übertragen, dort befüllt und wieder in die Schulverwaltung übertragen werden.
* NEW: Die Auswahl der Filterung der Fachzeilen nach der `Beurteilungsart` unter `Fächer anzeigen` ist geändert worden. Die Optionen sind nebeneinander als Schaltflächen angeordnet. Beim Ansichtswechsel innerhalb des Programms bleibt Ihre Auswahl gespeichert, beim Neustart des Programms wird die Standardauswahl auf `Alle (nicht editierbar)` zurückgesetzt.

## Version 9.0.3 (16.06.2022)

* FIX: Problem beim `Speichern unter` behoben

## Version 9.0.1 (04.03.2022)

* FIX: Beim 'Speichern unter' wird die Datei mit `Dateiname.mymx` an der gewählten Stelle gespeichert.

## Version 9.0.0 (04.01.2022)

Version 9 wurde veröffentlicht!

Eine Übersicht der Neuerungen finden Sie hier: [https://doc.magellan.stueber.de/changelog/neu.mag9/](https://doc.magellan.stueber.de/changelog/neu.mag9/)

## Version 8

### Version 8.0.14 (17.12.2021)

* FIX: Für Dateien, die mit der Version MAGELLAN 8.0.13 oder früher erstellt wurden, wird für Schüler denen derselbe Lehrer als Tutor und als Fachlehrer zugeordnet wurde, die Rolle des Fachlehrers ignoriert. Ab mit der Version MAGELLAN 8.0.14 oder höher erstellten MyMAGELLAN-Dateien tritt diese Problematik nicht mehr auf. Eine Vorabversion von MyMAGELLAN, die diese Problematik korrekt verarbeitet, finden Sie unter: [https://my.hidrive.com/lnk/ncSJCFHd](https://my.hidrive.com/lnk/ncSJCFHd)

### Version 8.0.13 (30.11.2021)

* FIX: Schlüsselverzeichnis Zeugnisbemerkungen wird in voller Länge aus MAGELLAN übergeben
* FIX: `Schüler > Ausbildung > Editieren` Tabulatorreihenfolge korrigiert
* FIX: Speichern der Eingaben auf der Karte `Zeugnisdaten` (besonderer Fall: nur eine Eingabefeld auf der Karte))

## Version 7

### Version 7.1.21 (04.12.2020)

* CHANGE: Filteransicht `Fächer`/`Schüler`: Spaltenposition und Gruppierungen bleiben bei Datensatzwechsel innerhalb der Ansicht erhalten (nicht bei Ansichtswechsel). Bei der Ansicht `Schüler` gibt es noch die Besonderheit, dass die Spalte `Kurs` immer die erste Spalte ist.
* CHANGE: Änderung des Ablaufs, Verarbeitung oder Bedienung

### Version 7.1.10 (05.05.2020)

* FIX: Anzeige der Inhalte der Verzeichnisfelder unter `Schüler > Zeugnisdaten korrgiert`
  * CHANGE: Die Anzeige der `Beurteilungsarten` unter `Fächer` ist angepasst worden. Statt des Drop-Downfeldes, sind jetzt Radio-Buttons verwendet worden, die dem Benutzer die gefilterte Darstellung der Liste nach der Beurteilungsart verdeutlichen. Bitte beachten Sie die angepasste Dokumentation unter [https://doc.mymagellan7.stueber.de/noteneingabe/#eingabe-nach-fachern](https://doc.mymagellan.stueber.de/noteneingabe/#eingabe-nach-fachern)
* CHANGE: Beim Öffnen der Ansicht `Fächer` ist wie bisher die Vorauswahl so getroffen, dass alle Schülerzeilen zum Fach gezeigt werden. In dieser Ansicht ist kein Editieren möglich. Bitte wählen Sie vor der Eingabe der Ergebnisse die gewünschte Beurteilungsart aus.
* FIX: Problem bei der Anzeige der Beurteilungsart in der Ansicht `Fächer` behoben.
* FIX: Problem bei der Eingabe in der Fächeransicht und Anzeige in der Schüleransicht behoben.
* FIX: Anzeige von Füllwerten korrigiert
* FIX: spaltenbezogene Filterkriterien in der Ansicht `Fächer` sichtbar

### Version 7.1.9 (07.04.2020)

* NEW: Neues Format für mym-Dateien (*.mymx). Neu erzeugte mym-Dateien werden als verschlüsselte XML-Dateien gespeichert. Zuvor exportierte Dateien im alten Format können aber weiterhin eingelesen werden
* FIX: In der Ansicht  `Fächer` und  `Schüler` sind die Felder `schriftl.Note1` - `Endnote (gesamt)` beschreibbar.
* FIX: Filter im Bereich
* CHANGE: in der Ansicht `Schüler` und `Fächer` wird die Spalte `Kurs` als erste Spalte eingeblendet, die das Fachkürzel plus die Kursnummer ausgibt.

### Version 7.1.7 (20.03.2020)

* FIX: unter Fächer eingeblendete Personalnummer bleibt auch beim Fachwechsel erhalten
* FIX: Filterung der Klassen in der linken Spalte der Schüleransicht korrigiert
* FIX: Ausgeblendete Spalten werden auch beim Datensatzwechsel beibehalten
* NEW: veränderter Umgang mit Fehlzeiten und der Option "beim Importieren überschreiben"

!!! danger "Achtung"

    Bitte beachten Sie die Abschnitt [Importlogik > Fehlzeiten](https://doc.magellan7.stueber.de/mymagellancenter/importlogik/#fehlzeiten)

* CHANGE: beim ersten Aufruf der Fächeransicht ist standardmäßig die Filter für die Beurteilungsart auf `alle Beurteilungsarten` gestellt
* NEW: In der Ansicht `Schüler` ist in der rechte Fensterhälfte links vor der ersten Spaltenbezeichnung das Symbol zum Aufruf des Untermenüs zum Ein- und Ausblenden von Spalten.

![Symbol zum Ein- und Ausblenden von Spalten verfügbar](/assets/images/changelog/7.1.7.00.png)

### Version 7.1.5 (05.02.2020)

* FIX: Listenfelder unter `Schüler > Zeugnisdaten` sind auswählbar
* Change: Mym7-Datei kann nicht mehrfach geöffnet werden

### Version 7.1.4 (03.02.2020)

* FIX: versehentlich eingetragene Mahnung kann wieder gelöscht werden
* FIX: zuletzt eingetragene Note wird vor dem Datensatzwechsel gespeichert
* FIX: Eingabe von Noten mit oder ohne Tendenz per Tastatur korrigiert
* FIX: Funktion der Vor- und Zurückschaltfläche im Bereich `Schüler` und `Fächer` überarbeitet

### Version 7.1.3 (08.01.2020)

* NEW: Eingabe der Leistungen per Ziffernblock und Pfeiltasten möglich
* FIX: Sortierung von Umlauten korrigiert
* CHANGE: Fachansicht: Die zuletzt gewählte Sortierung wird beim Wechsel zum nächsten Datensatz für die neue Liste wieder ausgeführt
* CHANGE: Schüleransicht: Die zuletzt gewählte Sortierung wird beim Wechsel zum nächsten Datensatz für die neue Liste wieder ausgeführt
* CHANGE: Beim Start einer MyMAGELLAN-Datei wird die Beurteilungsart der Fächeransicht standardmäßig mit der Auswahl `Alle Beurteilungsarten` voreingestellt. 

### Version 7.1.0 (30.10.2019)

* FIX: Problem der unzuverlässigen Darstellung des Reiters `Datenbank` behoben
* FIX: Speichern der Fenstergröße und Fensterposition angepasst
* CHANGE: Layout angepasst
