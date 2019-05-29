# Installation


 
## Systemvoraussetzungen

MyMAGELLAN ist kompatibel mit folgenden Betriebssystemen:

| MAGELLAN                  | Kompatibilität                                                                      |
| ------------------------- | ----------------------------------------------------------------------------------- |
| **Betriebssystem 32-Bit** | Windows  Vista / Windows  2008 / Windows  7 / Windows  8 / Windows  10              |
| **Betriebssystem 64-Bit** | Windows 7 /  Windows 8 /  Windows 10 /  Windows2008 /  Windows 2012 /  Windows 2016 |
| **Office-Versionen**      | Office  2007<br/>Office 2010<br/>Office 2013<br/>Office 2016                        |
| **Hardware**              | MAGELLAN benötigt keine besonderen Hardware-Anforderungen                           |
| **Bildschirmauflösung**   | Die Bildschirmauflösung sollte 1280x800 Bildpunkte nicht unterschreiten             |


## So installieren Sie MyMAGELLAN

Nachdem Sie die Installationsdateien für MyMAGELLAN in Absprache mit Ihrem Administrator erhalten haben, gehen Sie wie folgt vor:

1. Starten Sie Installation per Doppelklick auf die Datei „MyMAGELLAN.msi“ auf Ihrem Datenträger. Bestätigen Sie anschließend alle Fenster mit `Weiter` und `Fertigstellen`, das Programm wird auf Ihrem Rechner installiert.


![Bestätigen Sie mit Weiter!](/assets/images/installation/01.png)

![Klicken Sie auf Installieren!](/assets/images/installation/02.png)

![MyMagellan wird auf Ihrem Rechner installiert.](/assets/images/installation/03.png)

![Klicken Sie auf Fertigstellen!](/assets/images/installation/04.png)


MyMagellan ist auf Ihren Rechner installiert!

## So starten Sie MyMAGELLAN

Sie können jetzt MyMAGELLAN starten:

1. Klicken Sie auf Start links unten auf Ihrem Bildschirm.

2. Klicken Sie auf Programme, dann auf STÜBER SYSTEMS und dann auf MyMAGELLAN 7.
	
MyMAGELLAN 7 wird nun gestartet.


Öffnen Sie das Menü `Start > Programme > STÜBER SYSTEMS`, halten Sie die Taste Strg gedrückt, klicken Sie gleichzeitig mit der Maus auf MyMAGELLAN 7 und ziehen Sie das Programmsymbol mit gedrückter Maustaste auf Ihre Bildschirmarbeitsfläche. Sie können dann direkt auf das MyMAGELLAN-Symbol auf Ihrer Arbeitsfläche klicken, um MyMAGELLAN 7 zu starten.

Laden Sie jetzt Ihre MyMAGELLAN-Datei, die Sie von Ihrem Administrator erhalten haben. Gehen Sie dazu wie folgt vor:

| Nr         | Möglichkeit                                                                                                                                                         |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Variante 1 | Klicken Sie auf Datei und dann auf Öffnen. Wählen Sie die MyMAGELLAN-Datei aus und klicken Sie auf Öffnen.                                                          |
| Variante 2 | Alternativ können Sie das Programm auch öffnen, indem Sie doppelt auf die Datei (*.mym7) klicken, dann wird automatisch MyMAGELLAN gestartet und Ihre Datei geladen |


Nach dem Laden der Datei werden Sie ggf. nach dem Kennwort Ihrer MyMAGELLAN-Datei gefragt. Tippen Sie dazu das von Ihrem Administrator erhaltene Kennwort Ihrer Datei ein.



![Die Willkommensseite in MyMAGELLAN](/assets/images/screenshot1.png)

## Datensicherung

Das regelmäßige Erstellen von Sicherungskopien sollte für Sie zur Routine werden. Beugen Sie damit dem möglichen Verlust Ihrer Daten vor (Stromausfall, versehentliches Löschen usw.). Beachten Sie daher bitte folgende Ratschläge:

* Speichern Sie regelmäßig Ihre MyMAGELLAN-Datei mit der Endung .mym.

* Verwenden Sie mehr als ein Sicherungsmedium für Sicherungskopien und benutzen Sie diese der Reihe nach. So bleiben ältere Stadien der Daten erhalten.

* Bewahren Sie die Kopien an einem sicheren Ort auf.

!!! info "Hinweis"

	Sichern Sie Ihre Daten regelmäßig, am besten täglich. So können Sie ggf. auf ältere Stadien Ihrer Daten zurückgreifen.

## Aktualisieren per Gruppenrichtlinien oder Softwareverteilung

MyMAGELLAN 7 installiert sich in einen Ordner und die Registry, dafür müssten Zugriffsrechte gewährt werden:

| Was                         | Pfad am Beispiel Windows 10                       |
| --------------------------- | ------------------------------------------------- |
| Programmdateien (EXE etc.)) | C:\Program Files (x86)\Stueber Systems\Magellan 7 |

!!! info "Hinweis"

	Es wird das Recht benötigt in die Registry zu schreiben!

	Die Angaben variieren je nach Betriebssystem. Im oberen Beispiel beziehen sich die Angaben auf Windows 10!

Für die Installation von MyMAGELLAN 7 wie auch für das Update von MyMAGELLAN 7 benötigt der Benutzer Administratorenrechte bzw. er benötigt das Recht in Systemverzeichnisse ("C:\Programme" und "C:\Windows") zu schreiben und in die Registry unter HKEY-LOCAL-MACHINE zur schreiben. Das bedeutet, es könnte auch eine andere Benutzergruppe installieren, sofern diese die oben genannten Zugriffsrechte haben. Technisch gesehen sind Erstinstallation und Update gleich. 

Um die Updates möglichst ohne viel Aufwand auf mehreren Rechnern zu verteilen, gibt es zwei Möglichkeiten:

a. die Gruppenrichtlinien in einem Windows-Domänen-Netzwerk zu nutzen

b. Professionelle Software-Verteilung

* zu a.: Jeder Benutzer in einer Domäne kann bestimmte Rechte erhalten. Durch das Verwenden von Gruppenrichtlinien können diese Benutzer zu Gruppen zusammengefasst werden und dann diesen gesammelt Rechte zuweisen. Zum Beispiel könnten diese Gruppen das Recht haben bestimmte Programme zu installieren.

* zu b.: Es gibt verschiedene Programme zur automatisierten Softwareverteilung innerhalb eines Netzwerkes. Sie könnten so von zentraler Stelle aus die Installation der Updates anstoßen.

Grundsätzlich basiert unsere Installation auf der MSI-Technologie. Mit dieser MSI-Technologie wird beispielsweise auch MS Office installiert.

Folgenden Parameter sind möglich:

Silent-Setup für MyMAGELLAN 7:

| Installationstyp | Parameter                                                                |
| ---------------- | ------------------------------------------------------------------------ |
| Installation     | msiexec /i "C:\MySetup\MyMAGELLAN7.msi" /q APPDIR="C:\MyFolder\Magellan" |
| Deinstallation   | msiexec /x "C:\MySetup\myagellan7.msi" /q                                |

!!! info "Hinweis"

	`/i` bedeutet immer Installation und `/x`	 immer Deinstallation.

	Bitte starten Sie die Kommandozeilenaufrufe mit Administratorenrechten!

<figure class="center">
    <img src="/assets/images/eingabeaufforderung.als.admin.png" alt="Eingabeaufforderung per Rechtsklick mit administrativen Rechten starten!">
    <figcaption>Eingabeaufforderung per Rechtsklick mit administrativen Rechten starten!</figcaption>
</figure>
