# Modell: CHATGPT(o3 mini)
### Prompt um Prompt zu generieren (mit GPT-4o mini)
``` 
erstelle mir eine Prompt welche folgende Aufgabe in javascript umsetzen soll 
Kanban-Board mit:
Drei Spalten: "ToDo", "In Progress", "Done"
Drei Karten-Arten:
"Bug" (rot), "User Story" (grün), "Task" (blau)
Zwei Karten-Eigenschaen: Titel, Beschreibung,
Arbeitspacketgröße in Stunden
Erstellen und löschen von Karten
Verschieben von Karten per Drag&Drop
Dunkles Responsive Layout/Design
```
### Final Prompt
```
Erstelle eine Kanban-Board-Anwendung in JavaScript mit folgenden Anforderungen:

1. **Spalten:**
   - Drei Spalten: "ToDo", "In Progress", "Done"
   - Jede Spalte soll als Container für Karten fungieren.

2. **Karten-Arten:**
   - Es gibt drei Arten von Karten:
     - "Bug" (rot)
     - "User Story" (grün)
     - "Task" (blau)
   - Karten sollen dynamisch hinzugefügt werden können, wobei der Kartentyp ausgewählt wird (Bug, User Story, oder Task).

3. **Karten-Eigenschaften:**
   - Jede Karte soll die folgenden Eigenschaften haben:
     - **Titel** (Textfeld für den Titel der Aufgabe)
     - **Beschreibung** (Textfeld für eine detaillierte Beschreibung)
     - **Arbeitspaketgröße in Stunden** (Zahl, die die geschätzte Zeit für die Aufgabe in Stunden darstellt)

4. **Interaktive Funktionen:**
   - **Erstellen von Karten**: Benutzer können neue Karten mit den oben genannten Eigenschaften in jeder der drei Spalten erstellen.
   - **Löschen von Karten**: Jede Karte soll eine Löschoption haben, um sie zu entfernen.
   - **Verschieben von Karten**: Karten sollen per Drag & Drop zwischen den Spalten verschoben werden können.
   
5. **Design und Layout:**
   - **Dunkles Design**: Die Benutzeroberfläche soll ein dunkles Theme haben, mit passenden Farben für Hintergrund, Karten und Text.

   - **Responsive Layout**: Das Layout soll responsiv sein, sodass es auf verschiedenen Bildschirmgrößen gut funktioniert, einschließlich mobilen Geräten.
   
6. **Technische Anforderungen:**
   - Verwende HTML, CSS und JavaScript (optional: mit einer Bibliothek wie dragula.js oder react-beautiful-dnd für Drag&Drop).
   - Nutze ein flexibles Grid-System (z.B. CSS Flexbox oder CSS Grid), um die Spalten und Karten korrekt auszurichten und das Layout anzupassen.
   - Verwende JavaScript, um dynamisch Karten zu erstellen, zu löschen und zu verschieben.
   - Das verschieben von Karten soll eine flüssige animation haben, um die Seite grundsätzlich ansprechender aussehen zu lassen.
```
### Semantisches HTML
> :x: Nein, alles div-container

### Valides HTML
> :white_check_mark: Check (Trust me bro)

### Modernes JavaScript
> :white_check_mark: Check

### Clean Code
> :white_check_mark: Alles durchkommentiert, sieht gut aus

### Drag&Drop Feedback
> :white_check_mark: Dropzone leuchtet grau auf, wenn Element darüber gehalten wird

### Minimale Lösung
> :white_check_mark: Check

### Responsive Design
> :white_check_mark: Check