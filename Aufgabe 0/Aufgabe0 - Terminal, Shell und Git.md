# Assignment 0 – Terminal, Shell, Git & Markdown (macOS)

## Einleitung – Was ist das hier eigentlich?

Wenn du **noch nie programmiert hast**: keine Panik. Diese Aufgabe ist **nicht** dazu da, dass du alles sofort verstehst.

Sie ist dafür da, dass du:
- ein Gefühl dafür bekommst, **wie Entwickler:innen arbeiten**
- lernst, mit dem Computer **über Textbefehle** zu sprechen
- verstehst, dass Programmieren aus **vielen kleinen, einfachen Schritten** besteht

Du wirst Dinge sehen, die zuerst verwirrend wirken. Das ist normal. Niemand erwartet, dass du alles sofort kannst.

👉 Wichtig: **Du kannst nichts kaputt machen.** Im schlimmsten Fall funktioniert ein Befehl nicht – dann probierst du einen anderen.

---

## Überblick & Theorie (erst lesen)

Bevor du irgendetwas tust, lies diesen Abschnitt einmal komplett durch.  
Er erklärt die Werkzeuge, die du benutzen wirst, **in einfachen Worten**.

Du musst dir noch nichts merken – es geht nur darum, ein grobes Bild zu bekommen.

---

### Terminal
Das **Terminal** ist eine textbasierte Schnittstelle zu deinem Computer.

Statt zu klicken, schreibst du Befehle wie:
- „Zeig mir, wo ich bin“
- „Erstelle einen Ordner“
- „Führe dieses Skript aus“

📚 Hintergrund:
- [Terminal (Computer) – Wikipedia](https://de.wikipedia.org/wiki/Terminal_(Computer))

---

### Shell & Shellskripte
Die **Shell** ist das Programm, das deine Terminal-Befehle versteht.  
Ein **Shellskript** ist eine Datei mit mehreren solchen Befehlen.

Ein Skript sagt dem Computer:
> „Mach diese Schritte immer wieder genau so.“

📚 Hintergrund:
- [Shellskript – Wikipedia](https://de.wikipedia.org/wiki/Shellskript)

---

### VS Code (Code-Editor)
**VS Code** ist dein Werkzeug zum **Schreiben und Lesen** von Text, Code und Markdown.

Wichtig:
- Du schreibst **Dateien in VS Code**
- Du **führst Dinge im Terminal aus**

VS Code hilft dir durch:
- Farben für Code
- übersichtliche Ordneransicht
- integriertes Terminal
- Git-Unterstützung

👉 VS Code ist dein Hauptarbeitswerkzeug.

---

### Markdown (`.md`)
Markdown ist eine einfache Text-Sprache für Dokumentation.

Damit schreibst du:
- `README.md`
- Notizen
- Erklärungen

Markdown ist:
- leicht zu lesen
- leicht zu schreiben
- überall Standard

📚 Hintergrund:
- [Markdown – Wikipedia](https://de.wikipedia.org/wiki/Markdown)

---

### Git
**Git** merkt sich den Verlauf deines Projekts.

Git erlaubt dir:
- Änderungen bewusst zu speichern
- Fehler rückgängig zu machen
- deinen Lernfortschritt sichtbar zu machen

📚 Hintergrund:
- [Git – Wikipedia](https://de.wikipedia.org/wiki/Git)

---

## Ziel dieser Aufgabe

Du erstellst **ein einziges Projekt-Repository**, das vier kleine Teilaufgaben enthält.

Am Ende hast du:
- ein sauberes Projekt-Setup
- mehrere Commits
- ein README
- ein kleines Automatisierungs-Skript

---

## Aufgabenübersicht

Alle folgenden Aufgaben gehören **in dasselbe Repository**(Ordner) namens `terminal-basics`.

Du gibst **ein Projekt** ab, kein Sammelsurium einzelner Dateien.

---

## Wenn du nicht weiterkommst (wichtig)

Festzustecken gehört **zum Programmieren dazu**.  
Auch erfahrene Entwickler:innen sind ständig am Suchen, Lesen und Fragen.

Wenn du vor einem Problem stehst, gehe **immer in dieser Reihenfolge** vor:

### 1. Selbst nachdenken
- Lies die Fehlermeldung **genau**
- Was hast du erwartet?
- Was ist stattdessen passiert?

### 2. Internet-Suche
- Suche nach der **konkreten Fehlermeldung**
- Oder nach Stichwörtern wie:
  - „macOS terminal permission denied“
  - „git commit nothing to commit“
- Gute Quellen sind z. B.:
  - Stack Overflow
  - offizielle Dokumentationen
  - Blogposts

### 3. ChatGPT benutzen
- Beschreibe dein Problem so konkret wie möglich:
  - Was wolltest du tun?
  - Welchen Befehl hast du eingegeben?
  - Welche Fehlermeldung kam zurück?
- ChatGPT ist ein **Werkzeug**, kein Spickzettel.
  Verstehe die Antwort, bevor du sie ausprobierst.

### 4. Hilfe holen
Wenn du nach ehrlichem Probieren immer noch nicht weiterkommst:

📧 **E-Mail an:**  
**massimo@outblack.ch**

Schreibe kurz:
- was du machen wolltest
- was nicht funktioniert
- was du bereits versucht hast

👉 Wichtig: Hilfe holen ist kein Scheitern.  
Es ist Teil des Lernprozesses.

---

## Teil A – Terminal-Grundlagen (ca. 30–45 min)

### Was ist das Terminal?
Normalerweise klickst du dich mit der Maus durch Ordner und Fenster. Das **Terminal** ist ein anderes Interface:

- Du schreibst **Textbefehle**
- Der Computer antwortet ebenfalls mit Text

Das wirkt altmodisch, ist aber:
- extrem mächtig
- sehr präzise
- die Basis für fast alles in der Software-Entwicklung

📚 Hintergrund:
- [Terminal (Computer) – Wikipedia](https://de.wikipedia.org/wiki/Terminal_(Computer))

Stell dir das Terminal wie eine **Konversation mit dem Betriebssystem** vor.

Du sagst z. B.:
> „Wo bin ich gerade?"

Der Befehl dafür ist:
> `pwd`

---

### Aufgaben
1. Erstelle einen Ordner für Lernprojekte:
   - `~/dev/learning`
2. Erstelle darin den Ordner:
   - `terminal-basics`
3. Bewege dich im Dateisystem mit:
   - `pwd`, `ls`, `cd`
4. Erstelle Dateien und Ordner:
   - `mkdir`, `touch`
5. Zeige Datei-Inhalte an:
   - `cat`, `less`
6. Lerne diese Tastenkürzel:
   - Pfeil ↑ (Befehlsverlauf)
   - `Ctrl + A` (Zeilenanfang)
   - `Ctrl + E` (Zeilenende)
   - `Ctrl + C` (Abbrechen)
7. Nutze die Hilfe:
   - `man ls`
   - `man mkdir`

### Abgabe
- Erstelle die Datei: `notes/terminal.md`
- Schreibe **1–2 Sätze** zu jedem dieser Befehle:
  - `pwd`
  - `ls`
  - `cd`
  - `mkdir`
  - `touch`
  - `cat`
  - `less`
  - `echo`
  - `>`
  - `>>`

### Selbstkontrolle
- `ls -R` im Projektordner zeigt `notes/terminal.md`

---

## Teil B – Erstes Shell-Skript (ca. 45–60 min)

### Was ist ein Skript?
Ein Skript ist nichts Magisches.

Es ist:
- eine ganz normale Textdatei
- mit mehreren Terminal-Befehlen untereinander

Anstatt jeden Befehl einzeln einzutippen, sagst du:
> „Computer, merk dir diese Schritte und führ sie jedes Mal gleich aus."

Das ist **Automatisierung** – ein Kernprinzip beim Programmieren.

📚 Hintergrund:
- [Shellskript – Wikipedia](https://de.wikipedia.org/wiki/Shellskript)

In diesem Teil baust du dein **erstes kleines Programm**, auch wenn es noch kein Python ist.

--- (ca. 45–60 min)

### Idee
Ein Shell-Skript ist eine **Textdatei mit Befehlen**, die automatisch ausgeführt werden.

### Aufgaben
1. Erstelle die Datei `scripts/hello.sh`
2. Mache sie ausführbar
3. Beim Ausführen soll das Skript:
   - eine Begrüßung mit deinem Benutzernamen ausgeben
   - das heutige Datum ausgeben
   - einen Ordner `output/` erstellen (falls nicht vorhanden)
   - alle Ausgaben in `output/run.log` **anhängen**

### Hinweise (keine Lösung)
- Erste Zeile: `#!/bin/zsh`
- Benutzername kommt aus einer Umgebungsvariable
- Es gibt einen `date`‑Befehl
- Anhängen erfolgt mit `>>`
- Rechte ändern mit `chmod`

### Selbstkontrolle
- Wenn du das Skript zweimal ausführst, enthält `run.log` zwei Einträge

---

## Teil C – Git Grundlagen (ca. 45–60 min)

### Was ist Git?
Git ist ein **Versionskontrollsystem**.

Das bedeutet:
- Git merkt sich **jede Änderung** an deinen Dateien
- Du kannst jederzeit zu einem früheren Stand zurück
- Du siehst, *was* sich geändert hat und *wann*

Denk an Git wie an:
- eine Zeitmaschine für Code
- eine sehr genaue Undo-Funktion

📚 Hintergrund:
- [Git – Wikipedia](https://de.wikipedia.org/wiki/Git)

Wichtig: Git speichert nichts automatisch. **Du entscheidest bewusst**, wann ein Zustand gespeichert wird (Commit).

--- (ca. 45–60 min)

### Aufgaben
1. Initialisiere ein Git-Repository
2. Erstelle eine `.gitignore`, die ignoriert:
   - `output/`
   - `.DS_Store`
3. Erstelle sinnvolle Commits:
   - Commit 1: „Add terminal notes"
   - Commit 2: „Add hello script"
   - Commit 3: „Add gitignore"

### Befehle, die du kennen solltest
- `git init`
- `git status`
- `git add`
- `git commit`
- `git log`
- Bonus: `git diff`

### Selbstkontrolle
- `git status` → working tree clean
- `git log --oneline` zeigt mindestens 3 Commits

---

## Teil D – README & Markdown (ca. 30–45 min)

### Warum README?
Code ohne Erklärung ist wie ein Gerät ohne Anleitung.

Ein `README.md` ist:
- das Erste, was andere (und dein Zukunfts-Ich) lesen
- eine kurze Erklärung, **was hier passiert**

Markdown ist eine einfache Text-Sprache, mit der man:
- Überschriften
- Listen
- Code

schön lesbar formatieren kann – ohne komplizierte Tools.

--- (ca. 30–45 min)

### Aufgaben
Erstelle eine `README.md` mit:
- Titel
- Kurzbeschreibung des Projekts
- Anleitung zum Ausführen des Skripts
- Erklärung der Ausgabe
- Checkliste: Was habe ich gelernt?

### Markdown-Anforderungen
Verwende:
- Überschriften (`#`, `##`)
- Aufzählungen
- Einen Codeblock mit ```

### Selbstkontrolle
- `cat README.md` ist gut lesbar

---



👉 **Ziel dieser Aufgabe:** Du sollst dich im Terminal zuhause fühlen. Programmieren kommt danach.

---

## Bonus-Idee (empfohlen): Projekt-Bootstrap-Skript

Schreibe ein Shellskript, das automatisch:
- einen neuen Projektordner erstellt
- `git init` ausführt
- eine `README.md` anlegt
- eine sinnvolle Ordnerstruktur erzeugt

Beispiel:
```
./new-project.sh my-project
```

Dieses Skript soll dir zeigen:
> Computer können dir repetitive Arbeit abnehmen.

Viel Spass
