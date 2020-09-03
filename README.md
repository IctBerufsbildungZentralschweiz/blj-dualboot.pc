languageTool.language:de


# Wir bauen einen PC mit Dualboot
1. PC Assemblieren (zusammenbauen)
2. Beschreiben der Anschlüsse auf dem Mainboard
3. Betriebssystem Windows installieren
4. Dualboot mit Betriebsystem Linux einrichten
5. Gemeinsame Datenpartition erstellen
6. Virenschutz und Standard Applikationen
7. Vernetzung
8. Checkliste und Rückbau
9. Ergonomie am Arbeitsplatz



# 1. PC Assemblieren (zusammenbauen)
### Lernziel: Das Mainboard ist mit allen notwendigen Komponenten assembliert (CPU, RAM, GPU) und in das Gehäuse eingebaut. Der PC lässt sich starten.

> ***ACHTUNG:** Mache dich __vor__ dem Anfassen der Komponenten mit elektrostatischer Entladungen ESD vertraut und treffe Schutzmassnahmen!
-> [Video](https://www.youtube.com/watch?v=kwrfjVrIn50) & [Infos](https://www.bimos.com/B/ch-de/news/3009/die-wichtigsten-esd-schutzmassnahmen-fuer-eine-stoerungsfreie-arbeit)* 

> ***Tipp:** Überlegen dann bauen! Welche Komponenten verbaut man besser zuerst auf dem Mainboard bevor wir das Mainboard in das Gehäuse einbauen?* 

Werden die Komponenten im BIOS erkannt?

> ***Tipp:** Der Hersteller des Maiboards gibt Auskunft über welche Tastenkombination man ins BIOS gelangt.*

Setze das BIOS auf UEFI Modus. Mache Dich mit den Unterschieden UEFI, legacy BIOS vertraut. Wikipedia enthält einige Infos zu UEFI: [Unified Extensible Firmware Interface](https://de.wikipedia.org/wiki/Unified_Extensible_Firmware_Interface) welche Dir die Unterschiede erklären.

# 2. Beschreiben der Anschlüsse auf dem Mainboard
### Lernziel: Alle Anschlüsse auf dem Mainboard sind bezeichnet und die Funktion beschrieben (Word-Dokument)

Erstelle ein Foto von allen Anschlüssen auf dem Mainboard. Füge das Foto in ein Word-Dokument ein und bezeichne alle Anschlüsse. Beschreibe die Funktion der Anschlüsse und erkläre die Abkürzungen.

Gibt es Anschlüsse wo Du nicht kennst? Suche Dir die Infos im Internet dazu.

# 3. Betriebssystem Windows installieren 
### Lernziel: Windows ist installiert und lässt sich starten.

Besorge Dir das Windows ISO und erstelle Dir einen Boot fähigen USB-Stick, um damit das Windows auf dem PC zu installieren. Das ISO lässt sich auch ohne Windows Key installieren (60 Tage Demo)!

**-> Installiere Windows 10 Pro** [Download Windows ISO](https://cloud.ict-bz.ch/index.php/s/GGnQzQr4c2G6FFl)

> ***Tipp:** Mach Dir überlegungen zur Partitionierung der Festplatte! Macht es Sinn die Platte in mehrere [Partitionen](https://de.wikipedia.org/wiki/Partition_(Datentr%C3%A4ger)) zu unterteilen?*

> ***Tipp:** ISO Boot Stick einfach erstellen? [RUFUS](https://rufus.ie/) hilft!*

# 4. Dualboot mit Betriebssystem Linux einrichten
### Lernziel: Linux ist installiert und lässt sich starten. Dualboot ist korrekt konfiguriert und Windows oder Linux startet korrekt.

Als Linux Distribution verweden wir Ubuntu. Es gibt unzählige Distributionen mit oder ohne grafischer Oberfläche (GUI). Ubunutu ist die weitverbreitetste Distribution mit grafischer Oberfläche.

> ***Tipp:** Linux Distribution herunterladen und Boot Stick einfach erstellen? [UNetbootin](https://unetbootin.github.io/) hilft!*

# 5. Gemeinsame Datenpartition erstellen
### Lernziel: Wir können Daten zwischen Windows und Linux austauschen. Die verschiedenen Dateisysteme sind bekannt. Eine Datensicherung ist eingerichtet.

Wenn wir zwei verschieden Betriebssysteme auf dem PC haben, möchten wir trotzdem Daten untereinander austauschen können. Wie lösen wir das? Mache Dich mit den Unterschieden der Dateisysteme vertraut und notiere Dir diese.

> ***Tipp:** Mache Dir gedanken welches [Dateisystem](https://de.wikipedia.org/wiki/Dateisystem) Linux und Windows versteht.*

Daten sind wichtig, daher sollten diese auch regelmässig gesichert werden. Mache Dich mit der [3-2-1 Regel](https://www.veeam.com/blog/de/how-to-follow-the-3-2-1-backup-rule-with-veeam-backup-replication.html) bekannt und überlege Dir, wie Du die Datensicherung bei Deinem PC lösen würdest. Erstelle ein kleines Backup-Konzept.

Installiere eine Backup Software auf beiden Betriebssystemen (Linux und Windows) und richte einen Backup Job ein, welcher Deine Daten-Partition täglich sichert. Eine einfache Sicherung der Daten auf ein externes Medium reicht (eine Kopie).

> *Teste auch das Wiederherstellen der Daten! Funktioniert das einwandfrei?*

# 6. Virenschutz und Standard Applikationen

### Lernziel: Windows und Linux verfügen über einen Virenschutz. Die Standard Applikationen gemäss Liste sind installiert. Bedrohungen eines Betriebssystems sind bekannt.

Jedes Betriebssystem ist nicht vor Viren geschützt. Daher benötigt es einen Virenschutz. Suche im Internet nach einem kostenlosen Virenschutz und installiere diesen auf beiden Betriebssystemen. Es spielt keine Rolle, ob Du für beide Betriebssysteme den gleichen Virenschutz oder zwei unterschiedliche verwendest.

> ***Tipp:** Teste ob der Virenscanner funktioniert! Auf der Webseite vom [EICAR](https://www.eicar.org/) - European Institute for Computer Antivirus Research findest Du Test-Dateien.*

Erstelle ein Merkblatt, in welchem die folgende Malware erklärt wird: 

- Was ist ein Computervirus? 
- Was ist ein Trojaner? 
- Was ist ein Wurm? 
- Was ist ein Hoax?

> *Erkläre im Merkblatt auch die jeweilige Funktionsweise (Prinzip genügt) einer jeden Malware, sowie welche Schutzmassnahmen und Gegenmassnahmen getroffen werden können, respektive getroffen werden sollten, um Schäden zu vermeiden.*


Suche im Internet nach OpenSource oder Freeware Applikationen und installiere diese auf beiden Betriebssystemen:

- Office Applikation
- Bildbearabeitung
- ZIP Programm
- PDF Reader
- Web Browser

# 7. Vernetzung

### Lernziel: Windows und Linux können auf dem Schulzimmer-Drucker erfolgreich drucken. Netzlaufwerk für Datenaustausch unter Windows und Linux sind eingerichtet.

Wir vernetzen den PC über einen Switch mit dem PC der anderen Gruppe. Wir möchten mit der anderen Gruppe Daten austauschen. Dazu geben wir die Datenpartition frei und richten unter Windows und Linux ein Netzlaufwerk ein.

> ***Tipp:** Windows und Linux verstehen sich gut, sofern man die richtigen Protokolle benutzt. Windows verwendet SMB für den [Datenaustausch](https://www.pcwelt.de/ratgeber/Windows-und-Linux-Freigaben-einrichten-9790088.html). Linux nennt das Protokoll Samba.*

Sprecht mit der anderen Gruppe ab, wer die Freigabe unter Windows einrichtet und wer die Verbindung zur Freigabe unter Linux einrichtet. Die Gruppe wo unter Linux die Verbindung zur Freigabe eingerichtet hat, gibt nachher Ihre Datenpartition unter Linux frei und die andere Gruppe richtet eine Verbindung unter Windows zu dieser ein.

> *Jede Gruppe muss auf der Freigabe Dateien lesen, löschen und erstellen können. Mache Dich mit den Berechtigungen in [Windows](https://blog.netwrix.de/2020/01/02/unterschiede-zwischen-freigabe-und-ntfs-berechtigungen/) und [Linux](https://praxistipps.chip.de/ubuntu-zugriffsrechte-aendern-so-gehts_49353) vertraut.*


# 8. Checkliste und Rückbau

Abschluss der Arbeiten gemäss diesen Punkten:
- [Checkliste](https://cloud.ict-bz.ch/index.php/s/vrHwacMdcUX2820) ist abgearbeitet
- Komponenten sind zurückgebaut

# 9. Ergonomie am Arbeitsplatz

### Lernziel: Kennen der ergonomischen Richtlinien für den Computer-Arbeitsplatz

Lese auf der Webseite der [SUVA](https://www.suva.ch/de-CH/material/Dokumentationen/bildschirmarbeit-wichtige-informationen-fur-ihr-wohlbefinden) die Informationen zum Thema Ergonomie am Computer-Arbeitsplatz durch. Notiere Dir die wichtigsten Merkmale für einen ergonomischen Computer-Arbeitsplatz und erstelle ein Merkblatt (in A3) mit den wichtigsten Gesundheitstipps für das Arbeiten am Computer.

Überprüfen Deinen bestehenden Arbeitsplätz auf ergonomische Aspekte hin. Sind die Arbeitsplätze ergonomisch korrekt eingerichtet? Gibt es Verbesserungspotenzial?