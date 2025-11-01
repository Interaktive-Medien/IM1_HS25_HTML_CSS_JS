# Lektion 3: JavaScript Grundlagen

## Lernziele

Nach dieser Lektion können Sie:
- JavaScript-Dateien mit HTML verbinden
- Die Browser-Konsole nutzen
- Einfache JavaScript-Ausgaben erstellen
- Grundlegende Interaktivität programmieren

## Inhalte

### 📚 Lesson (Theorie)
Im Ordner `lesson/` finden Sie Dokumentation zu:
- JavaScript-Einbindung
- console.log() zur Fehlersuche
- DOM-Manipulation
- Event-Listener

### 💡 Examples (Beispiele)
Im Ordner `examples/` finden Sie praktische Beispiele

### ✏️ Exercises (Übungen)
Im Ordner `exercises/` können Sie üben

## Wichtige Konzepte

### JavaScript-Einbindung
```html
<script src="script.js"></script>
```
**Wichtig:** Das `<script>`-Tag sollte am Ende des `<body>` stehen!

### Console.log()
```javascript
console.log("Hallo Welt!");
console.log("Meine erste JavaScript-Ausgabe");
```

### DOM-Manipulation
```javascript
// Element selektieren
const button = document.querySelector('.primary-button');
const counter = document.getElementById('counter-value');

// Element verändern
counter.textContent = "Neuer Text";
```

### Event-Listener
```javascript
button.addEventListener('click', () => {
  console.log("Button wurde geklickt!");
});
```

## Aufgabe

1. Erstellen Sie eine JavaScript-Datei (`script.js`)
2. Verknüpfen Sie diese mit Ihrer HTML-Datei
3. Schreiben Sie einen `console.log()` Befehl
4. Öffnen Sie die Browser-Konsole (F12) und überprüfen Sie die Ausgabe
5. **Bonus:** Fügen Sie einen Button hinzu, der bei Klick eine Aktion ausführt

## Developer Tools

Die Browser-Konsole öffnen Sie mit:
- **Chrome/Edge:** F12 oder Rechtsklick → "Untersuchen"
- **Firefox:** F12 oder Rechtsklick → "Element untersuchen"
- **Safari:** Cmd+Alt+I (Mac)

## Häufige Fehler

### "Mein JavaScript funktioniert nicht!"
- ✅ Browser-Konsole geöffnet (F12)? Was steht dort?
- ✅ `<script>`-Tag am Ende des `<body>`?
- ✅ Dateipfad korrekt? (`src="js/script.js"`)
- ✅ Datei gespeichert?

### "Cannot read property of null"
```javascript
// Häufiger Fehler:
const button = document.getElementById('myButon');  // Tippfehler!
button.addEventListener('click', ...);  // ERROR

// Lösung: ID-Namen überprüfen
const button = document.getElementById('myButton');
```

### "Nichts passiert beim Klick!"
- ✅ Event Listener korrekt? (`addEventListener`)
- ✅ Element-ID stimmt mit HTML überein?
- ✅ Funktion korrekt geschrieben?

### "console.log() zeigt nichts an!"
- ✅ Browser-Konsole geöffnet? (F12)
- ✅ Im richtigen Tab? (Console, nicht Elements)
- ✅ Rechtschreibung korrekt? (`console.log`, nicht `console.log`)

**Mehr Hilfe:** [Häufige Fehler & Lösungen](../00-course-info/haeufige-fehler-und-loesungen.md#-javascript-fehler)

## Nächste Schritte

Nach Abschluss dieser Lektion fahren Sie fort mit:
→ **04-css-layouts** - Lernen Sie fortgeschrittene Layout-Techniken
