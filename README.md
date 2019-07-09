# ![](https://www.lpice.eu/fileadmin/_processed_/csm_LinuxEssentials-01_0ab118aa19.jpg) myE010 - Linux Essentials Exam 010

Beispiel für einen Aufbau einer Dokumention des Lern- und Entwicklungsprozesses mit Ausgesuchten Unterkapiteln aus einem oder beiden LPI Examen



## Fahrplan
***


| Datum | behandelte Unterrichtsinhalte: | Gewichtung |
| -------- | ------ | -------- |
| 15.05.19 | Installation SW, Einrichten Linux VM<br>1.1 Linux Evolution and Popular Operating Systems<br>1.3 Open Source Software and Licensing | 2 + 2 |
| 22.05.19 | [2.1 Command Line Basics](https://github.com/w901-fr19-mi/E010#21-command-line-basics)<br>[2.3 Using Directories and Listing Files](https://github.com/w901-fr19-mi/E010#23-using-directories-and-listing-files)<br>2.4 Creating, Moving and Deleting Files  | 2 + 3 + 2 |
| 29.05.19 | 3.2 Searching and Extracting Data from Files<br>3.3 Turning Commands into a Script | 3 + 4 | 
| 05.06.19 | 4.4 Your Computer on the Network | 2 |
| 12.06.19 | 702.1 Container Usage - Studium | - |
| 19.06.19 | 702.1 Container Usage - Umsetzung | 7 |
| 26.06.19 | LB1 Theoretische Prüfung und Abschluss LB2 | - |
| 03.07.19 | Sommersporttage | - |
|          | Total Punkte | 24 !


## Dokumention des Lern- und Entwicklungsprozesses
***

### Kapitel: 1.1 Linux Evolution and Popular Operating Systems

**Weight**: 2

**Beschreibung**: Knowledge of Linux development and major distributions

**Tagesziele**: Einführung in Linux 

**Vorgehen**: Theorie lesen

**Arbeitsergebnisse**
* Red Hat wurde 1993 unter dem Namen »ACC Corporation« als Vertriebsfirma für Linux- und Unix-Zubehör gegründet.
* Die Firma SUSE wurde 1992 unter dem Namen »Gesellschaft für Software- und System-Entwicklung« als Unix-Beratungshaus gegründet.
* Im Gegensatz zu den beiden großen Linux-Distributionsfirmen Red Hat und Novell/SUSE ist das Debian-Projekt ein Zusammenschluss von Freiwilligen.
* Der wahrscheinlich populärste Debian-Ableger ist Ubuntu, das von der britischen Firma Canonical Ltd. des südafrikanischen Unternehmers Mark Shuttleworth angeboten wird.


### Kapitel 1.3 Open Source Software and Licensing

**Weight**: 2

**Beschreibung**: Open communities and licensing Open Source Software for business

**Tagesziele**: Wissen über Urheberrechte und Lizenzen in Linuxsystemen anschaffen

**Vorgehen**: Theorie lesen

**Arbeitsergebnisse**

Urheberrecht bedeutet dass dem Urheber eines Werks, also dem Autor eines Buchs, Maler eines Bildes, … das Recht zuerkannt wird, als Einziger darüber zu verfügen, was mit dem Werk passiert.
Urheber können Rechte, in Form einer Lizenz, an andere weitergegeben

Die Lizenzen für freie und Open-Source-Software dienen dazu, dem Erwerber der Software Dinge zu erlauben, die er laut Urheberrechtsgesetz eigentlich nicht haben dürfte.
* Copyleft-Lizenz: GPL (u.a. eingesetzt für den Linux Kernel) soll sicherstellen, dass Software, die einmal unter der GPL steht, auch weiter unter der GPL bleibt.
* Ohne Copyleft: Apache, BSD, MIT. Software kann in seine eigenen Programme integriert und diese Programme in ausführbarer Form weitergeben werden.


### Kapitel 2.1 Command Line Basics

**Weight**: 2

**Beschreibung**: Basics of using the Linux command line

**Tagesziele**: Basic Linux Befehle kennenlernen 

**Vorgehen**: Vorgegebene Fachbegriffe mit hilfe von Google erklären

**Arbeitsergebnisse**
* Bash: Bash ist eine freie Unix-Shell 
* echo: Mit echo kann man Meldungen aus Text und Variabeln dem User zurückgeben
* history: Mit history hat man Zugriff auf die benutzten Befehlen der gleichen terminal session
PATH environment variable: It is a colon delimited list of directories that your shell searches through when you enter a command 
* export: the export command marks an environment variable to be exported with any newly forked child processes and thus it allows a child process to inherit all marked variables.
* type: type command is used for displaying information about command type

### Kapitel 2.3 Using Directories and Listing Files

**Weight**: 3

**Beschreibung**: Navigation of home and system directories and listing files in various locations

**Tagesziele**: Repetition der Orientierung in der Linuxumgebung

**Vorgehen**: Mir bekannte Befehle notieren und weitere mir wichtig erscheinende neue Befehle nachlesen.

**Arbeitsergebnisse**: 
* ls: Liste aktueller Unterordner
* cd ~: Wechsel ins eigene Home-Verzeichnis
* cd -: Auf das zuletzt verwendete Verzeichnis wechseln
* sudo: Ausführen eines Befehls als root (Admin)
* mount: einhängen/aushängen und anzeigen von Filesystemen
* mv: (move) verschieben einer Datei
* mkdir: Neues Verzeichnis (Ordner) erstellen

**Fazit und Aussicht**: Mit etwas einlernen kann ich wieder die Wichtigsten Befehle auswendig

### Kapitel 2.4 Creating, Moving and Deleting Files

**Weight**: 2

**Beschreibung**: Create, move and delete files and directories under the home directory

**Tagesziele**: Lernen wie ich mit Dateien im Linuxverzeichnisumfeld umgehen kann

**Vorgehen**: Bedeutung der Angegebenen Befehlen nachlesen.

**Arbeitsergebnisse**
* mv: (move) verschieben einer Datei
* cp: (copy) kopieren einer Datei
* rm: (remove) löschen einer Datei
* touch: Zugriffs- und Änderungs-Zeitstempel von Dateien ändern, oder neue Datei erstellen
* mkdir: Neues Verzeichnis (Ordner) erstellen
* rmdir: Löschen eines leeren Verzeichnis
* rm: Löschen eines Verzeichnis und dessen Inhalt

Case sensitivity:
Linux beachtet Gross-/Kleinschreibung, um so mehr Befehle bereitstellen zu können.

**Fazit und Aussicht**: simple globbing verstehe ich nicht.


### Kapitel 3.2 Searching and Extracting Data from Files

**Weight**: 3

**Beschreibung**: Search and extract data from files in the home directory

**Tagesziele**: Piping besser kennenlernen

**Vorgehen**: Vergleich zum Piping in Windows verstehen

**Arbeitsergebnisse**
Piping wird mit dem "|" Zeichen eingegeben. Man kann einen Befehl eingeben und mit der Pipe die Ausgabe manipulieren.
* cat: Zusammenfügen von Dateien 
* head, tail: Anfang und Ende von Dateien
* wc: zählt die Anzahl Wörter, Zeilen
* sort: Sortiert die Zeilen seiner Eingabe 
* uniq: Entfernt doppelte Einträge
* cut: Extrahiert Felder oder Spalten aus seiner Eingabe
* grep: Sucht in Dateien nach Zeilen mit bestimmtem Inhalt

**Fazit und Aussicht**: Das Piping in Linux habe ich davor nie angewendet gehabt.

### Kapitel 3.3 Turning Commands into a Script

**Weight**: 4

**Beschreibung**: Turning repetitive commands into simple scripts einer Linuxumgebung Scripts anwenden kann

**Vorgehen**: Angegebene Bekannte zuerst beschreiben.

**Arbeitsergebnisse**

* #! (shebang): Diese Zeichenkombination indiziert Zeilen des Scripts, die beim Aufruf des Files ausgeführt wird 
* /bin/bash: Definiert das der Script mit der Bash ausgeführt werden soll, und nicht mit einer anderen Shell
* Variables: Vordefinerte Variabeln sind vom System integriert
* Arguments: Linuxbefehle in Scripts
* for loops: Führt dazu das ein Befehl wiederholden Ausgeführt wird.
* echo: Unter Windows als Ping bekannt
* Exit status: Wenn ein Script erfolgreich durchgeführt wurde errecht es den Exit Status

Mein bevorzugter Linux-Texteditor ist Nano

**Fazit und Aussicht**: Ich habe sonst nie einen Script auf Linux zum laufen gebracht. 

### Kapitel 4.4 Your Computer on the Network

**Weight**: 2

**Beschreibung**: Querying vital networking configuration and determining the basic requirements for a computer on a Local Area Network (LAN).

**Tagesziele**: Wissen wie ich Einsicht in den Status meiner Linuxmaschine bekomme.

**Vorgehen**: Nachlesen und dann auf meiner Linux VM ausprobieren.

**Arbeitsergebnisse**
* route, ip route show: Anzeigen der IP Routingtabelle
* ifconfig, ip addr show: Anzeigen der IP-Konfigurationen
* netstat, ss: Anzeigen von Netzwerkverbindungen, Routingtabellen und Interface Statistiken
* /etc/resolv.conf, /etc/hosts: In diesen Konfigurationsdateien kann das OS z.B. den DNS eintrag nachschauen.

**Fazit und Aussicht**: Dies ist wichtiges Wissen für die Saubere verwendung von Linux.


-----------------------
Vorlage:
-----------------------
### Kapitel

**Weight**:

**Beschreibung**:

**Tagesziele**:

**Vorgehen**:

**Arbeitsergebnisse**

**Fazit und Aussicht**:

------------------------------------------
## Links

* [Linux Essentials Exam 010](https://www.lpi.org/our-certifications/exam-010-objectives)
* [E010 Dokumentation](https://github.com/w901-fr19-mi/E010) 
* [myE010 Original Repository](https://github.com/w901-fr19-mi/myE010)

