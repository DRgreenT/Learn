# Software Engineering_(DE)

## 1. Idee & Anforderungserhebung

---

### Ziel:

Was soll das Programm tun? Wer wird es nutzen? Welche Funktionen sind notwendig?
Vorgehen:

- Schreibe in einfachen Sätzen auf, was dein Programm können soll (User Stories).

Fragen, die du dir stellen kannst:
- Wer nutzt die Anwendung?
- Welche Kernfunktionen sind wichtig?
- Welche Plattformen (Windows, Linux, Mobile, Web)?
- Brauche ich eine Datenbank?

### Tools:

- Notiz-Apps: OneNote, Obsidian, Joplin, Google Keep
- Mindmaps: XMind, FreeMind, draw.io (Diagramm-Tool)
- User Stories: Trello, Notion (Kanban-Board mit Aufgaben)

---

## 2. Planung & Design

### Ziel:

Erarbeite einen Plan für den Aufbau – sowohl technisch (Architektur) als auch aus Sicht der Benutzeroberfläche (UI).
Vorgehen:

- Skizziere die Hauptkomponenten: z. B. Module, Services, Klassen.
- Plane den Ablauf / die Datenflüsse (z. B. Eingabe → Verarbeitung → Ausgabe).
- Wenn UI dabei ist: Mockups oder einfache UI-Skizzen zeichnen.
- Datenbankdesign ggf. mit Tabellenmodell planen.

### Tools:

- Draw.io oder Lucidchart für Flussdiagramme, ER-Diagramme, Klassendiagramme
- Figma oder Balsamiq für UI-Mockups
- Markdown (z. B. in Obsidian oder VS Code) zur Dokumentation
- DbDesigner oder SqlDBM für Datenbankschemata

---

## 3. Projektstruktur & Setup

### Ziel:

Ein sauberes Setup deiner Entwicklungsumgebung und Ordnerstruktur.
Vorgehen:

- Richte ein Git-Repository ein.
- Plane deine Projektstruktur (Ordner für Models, Services, UI usw.).
- Erstelle ggf. eine README.md mit Projektziel und Installationshinweisen.

### Tools:

- Git & GitHub / GitLab / Bitbucket
- Visual Studio / Visual Studio Code
- .gitignore generator: https://gitignore.io

---

## 4. Entwicklung

### Ziel:

Jetzt wird wirklich programmiert – idealerweise in kleinen Schritten mit Tests.
Vorgehen:

- Arbeite iterativ: kleine Features entwickeln, testen, committen.
- Nutze „Testdaten“ für die Entwicklung.
- Schreibe Kommentare und Logs, um Fehler besser zu verstehen.

### Tools:

- Debugger deiner IDE
- Logger (z. B. Serilog, NLog, Konsolenausgabe)
- Unit-Tests mit NUnit, xUnit, MSTest (bei wachsendem Projekt sinnvoll)

---

## 5. Dokumentation & Visualisierung

### Ziel:

Code verständlich dokumentieren und ggf. die Funktionsweise visualisieren.
Vorgehen:

- Kommentiere schwierige Methoden.
- Dokumentiere API-Endpunkte (z. B. mit Swagger).
v- Schreibe ein kleines Handbuch oder README für andere.

### Tools:

- Swagger/OpenAPI für WebAPIs
- Doxygen für C#, C++, Java
- Markdown-Reader oder Notion zur lesbaren Dokumentation

---

## 6. Deployment / Veröffentlichung
Ziel:

Dein Programm bereitstellen, testen und ggf. Updates einbauen.
Vorgehen:

- Plane, wie dein Tool verteilt wird (Installer, ZIP, WebApp, Docker…).
- Teste es auf einem anderen Rechner.
- Baue ggf. ein kleines Update-System oder Versionierung ein.

### Tools:

- InnoSetup / NSIS (Installer für Windows)
- GitHub Releases / ZIP-Archiv
- Docker (wenn du Erfahrung sammelst)
- CI/CD mit GitHub Actions (später sinnvoll)

---

## 7. Reflexion & Verbesserung

### Ziel:

Aus Fehlern lernen und dein Projekt verbessern.
Vorgehen:

- Was hat funktioniert? Was war schwer?
- Wo könntest du Code vereinfachen?
- Gibt es wiederverwendbare Teile (Library)?

---

## BONUS: Toolchain-Empfehlung für Einsteiger

- Planung	-> draw.io, Trello, Notion
- Dokumentation	-> Obsidian, Markdown
- Code schreiben	-> Visual Studio / VS Code
- Versionsverwaltung	-> Git, GitHub Desktop
- Debugging	-> Visual Studio Debugger
- UI-Mockups	-> Balsamiq, Figma
- Datenbankdesign	-> DBDesigner, SqlDBM
- API-Doku	-> Swagger (Swashbuckle bei C#)
