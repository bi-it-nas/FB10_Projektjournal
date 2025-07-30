# FB10_Projektjournal
---
# Dokumentation & Präsentation

## Inhaltsverzeichnis
* [Projektbeschreibung](#projektbeschreibung)
* [Benutzeranleitung](#benutzeranleitung)
* [Modifikationsanleitung](#modifikationsanleitung)
* [Chronologie und technische Herausforderungen](#chronologie-und-technische-herausforderungen)
* [Resources](#resources)
* [Ablauf](#ablauf)
* [Journal](#journal)
* [Gedanken](#gedanken)
* [Prototyp in Figma](#prototyp-in-figma)
* [Reviews](#reviews)

## Projektbeschreibung

Im Rahmen von diesem Projekt habe ich eine Android App entwickelt, welche eine Liste von Kursen und Sommerzeitaktivitaeten anzeigt  
Man kann diese Kurse anwählen, genauere Details dazu einlesen und schliesslich mit einem Emoji bewerten sowie einen optionalen Kommentar hinterlassen  
Die App ist gedacht fuer Teilnehmer dieser Kurse

## Benutzeranleitung

Die App zu bedienen ist einfach und intuitiv  
Auf der Startseite befindet sich eine Liste mit allen Kursen  
Man kann die Kurse antippen und es erscheint ein Popup Fenster mit weiteren Details sowie der Moeglichkeit, eine Bewertung abzugeben und einen optionalen Kommentar zu hinterlassen  

Die Bewertungen koennen jederzeit geaendert werden  
Auf der Startseite gibt es in der Titelleiste zwei zusaetzliche Buttons  
* Ein Button fuer die Einstellungen, wo man zurzeit alle Kommentare und Bewertungen loeschen kann  
* Ein Button zum Beenden der App  

## Modifikationsanleitung

Zurzeit ist es noch nicht moeglich, ueber die Einstellungen viel anzupassen  
Im CSharp Code kann man jedoch mit Kenntnissen in XAML, CSS und CSharp relativ viel an der Aesthetik veraendern, wie zum Beispiel Farben, Schriftarten, Schriftgroessen und Bilder  
Diese Anpassungen koennen alle im Resources Ordner vorgenommen werden

## Chronologie und technische Herausforderungen

Die App wurde bewusst sehr einfach gehalten zugunsten der Benutzerfreundlichkeit  

Bei der Entwicklung gab es einige technische Herausforderungen  
* Kenntnisse zu Animationen  
* Daten als JSON speichern und wieder laden  
* Verstaendnis der .NET MAUI Ordnerstruktur  
* LowLevel technisches Verstaendnis  

Die Arbeit in der .NET MAUI Umgebung war anspruchsvoll und stellte einen grossen Sprung dar  

## Resources

### Markdown
* [Markdown in 60s](https://www.youtube.com/shorts/4z0l5Kl2Q6E)
* [Holy Bible of Markdown](https://www.youtube.com/watch?v=_PPWWRV6gbA)

## Ablauf

### Phase 1 Setup & Initialisierung
* Installieren der Visual Studio Komponenten und Erstellen einer Hello World App  
  * Sicherstellen, dass die App im Emulator lauffaehig ist  
  * Upload auf GitHub unter dem Namen **HelloWorldMAUI**  
* Anleitung Erstellen Ihrer ersten .NET MAUI App von Microsoft folgen  
  * [Einfuhrung – Training | Microsoft](https://learn.microsoft.com)

#### Meilenstein 1
* Vorstellung der Hello World Applikation bei der FW Leitung und Einholung des Go zum Weiterfahren

### Phase 2 Planung
* Mockup Skizze erstellen (visuelle Darstellung ohne interaktive Elemente), z B mit  
  * [Figma](https://www.figma.com)  
  * [Draw io](https://www.draw.io)  
* UML Klassendiagramm erstellen inkl Methoden  
* Formular und Validierungen definieren

#### Meilenstein 2
* Vorstellung der Planung bei der FW Leitung und Einholung des Go zum Weiterfahren

### Phase 3 Umsetzung
* Entwicklung gemaess Phase 2  
* Git lokal nutzen siehe [Mit Git Projekten experimentieren](https://docs.github.com/de/get-started/quickstart/experimenting-with-git)  
* Laufende technische Dokumentation im Projektjournal auf GitHub  
* Erste lauffaehige Version upload ins espas Bsp Space unter Moodtracker  
  * URL: `https://github.com/espas-bsp/MEIN_KUERZEL_E810_MoodTracker`

#### Meilenstein 3
* Spätestens Mittwoch 9 7 2025 funktionsfaehige Version im IT Labor praesentieren  
* Nach erfolgreicher Zwischenpraesentation Zuteilung eines Gruppenpartners

### Phase 4 Technische Reflexion
* Beschreibung der groessten technischen Herausforderungen mind 3  
* Darstellung des Loesungswegs zu jeder Herausforderung

### Phase 5 Qualitaetssicherung durch Peer Review
* Peer Reviews werden rechtzeitig bekanntgegeben  
* Abhaengig vom jeweiligen Projekt

### Phase 6 Abschluss & Praesentation
* Ausfuehrliche Abschlusspraesentation laut Vorgabe

## Journal

### Mittwoch 9 Juli 2025  
09 00 – 10 00 > Projektstruktur anpassen und Ordner aufräumen  
10 15 – 11 55 > UI Layout für Kursliste verfeinern  
13 00 – 15 00 > Popup Details implementieren  
15 15 – 17 00 > Erste Emoji-Buttons einbinden

### Donnerstag 10 Juli 2025  
09 00 – 10 00 > Bewertungsspeicherung als JSON testen  
10 15 – 11 55 > Kommentar-Feld Validierung (Mindestzeichen)  
13 00 – 15 00 > Settings-Popup löschen-Funktion einbauen  
15 15 – 17 00 > Cache Laden/Nachladen prüfen

### Freitag 11 Juli 2025  
09 00 – 10 00 > Farben- und Schriftkonstanten refaktorisieren  
10 15 – 11 55 > Ressourcenordner Struktur optimieren  
13 00 – 15 00 > Automatisierte UI-Tests schreiben  
15 15 – 17 00 > Fehlerbehebung bei Popup-Animation

### Mittwoch 16 Juli 2025  
09 00 – 10 00 > Persistenz nach App-Neustart prüfen  
10 15 – 11 55 > Datenmodell Klassen erweitern  
13 00 – 15 00 > UML Klassendiagramm aktualisieren  
15 15 – 17 00 > Git Commit History bereinigen

### Mittwoch 23 Juli 2025  
09 00 – 10 00 > Benutzeranleitung im README ergänzen  
10 15 – 11 55 > Markdown Inhaltsverzeichnis testen  
13 00 – 15 00 > Platzhalter für Screenshots einfügen  
15 15 – 17 00 > Feedback-Reviews einarbeiten

### Donnerstag 24 Juli 2025  
09 00 – 10 00 > Animationen Feintuning  
10 15 – 11 55 > Popup Closing-Animation beheben  
13 00 – 15 00 > Icon-Assets ins Projekt importieren  
15 15 – 17 00 > Performance-Profiling durchführen

### Freitag 25 Juli 2025  
09 00 – 10 00 > Letzte UI-Anpassungen vornehmen  
10 15 – 11 55 > Endgültige Tests auf Emulator durchführen  
13 00 – 15 00 > README auf Rechtschreibung prüfen  
15 15 – 17 00 > Finaler GitHub-Upload

### Dienstag 29 Juli 2025  
09 00 – 10 00 > Vorbereitung Abschlusspräsentation  
10 15 – 11 55 > Folienstruktur erstellen  
13 00 – 15 00 > Screenshots einfügen und beschriften  
15 15 – 17 00 > Probedurchlauf Präsentation

### Mittwoch 30 Juli 2025  
09 00 – 10 00 > Feedback aus Probedurchlauf umsetzen  
10 15 – 11 55 > Letzte Code-Reviews durchführen  
13 00 – 15 00 > Abschlussdokumentation finalisieren  
15 15 – 17 00 > Abschlusspräsentation hochladen  

## Gedanken

Hier koennen Ideen, offene Fragen und ToDos notiert werden

## Prototyp in Figma

Prototype fuer Android Compact ChatGPT empfiehlt Frame  
Android Medium (412 × 927)

![image](https://github.com/user-attachments/assets/52f16e8a-010e-4ecb-b252-37d6129611e1)

This is a good safe mid range Android screen size Represents a modern phone in portrait orientation Big enough to design comfortably without going too large

## Reviews

Amazing 🌟 They absolutely loved it This is better than fun  
Fun 😄 They had a great time and enjoyed themselves  
Okay 👌 It was fine but nothing special  
Boring 😴 They found it dull or uninteresting  
Frustrating 😟 They found it difficult or got discouraged


