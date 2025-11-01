# Lektion 2: CSS Grundlagen

## Lernziele

Nach dieser Lektion können Sie:
- CSS-Dateien mit HTML verbinden
- Element-, Klassen- und ID-Selektoren verwenden
- Grundlegende CSS-Eigenschaften anwenden
- Farben, Abstände und Schriftarten gestalten

## Inhalte

### 📚 Lesson (Theorie)
Im Ordner `lesson/` finden Sie Dokumentation zu:
- CSS-Verknüpfung mit HTML
- Selektoren (Element, Klasse, ID)
- Wichtige CSS-Eigenschaften

### 💡 Examples (Beispiele)
Im Ordner `examples/` finden Sie praktische Beispiele

### ✏️ Exercises (Übungen)
Im Ordner `exercises/` können Sie üben

## Wichtige Konzepte

### CSS-Verknüpfung
```html
<link rel="stylesheet" href="style.css">
```

### Selektoren
```css
/* Element-Selektor */
h1 {
  color: blue;
}

/* Klassen-Selektor */
.card {
  background: white;
  padding: 20px;
}

/* ID-Selektor */
#main-title {
  font-size: 2rem;
}
```

### Wichtige Eigenschaften
- `color` - Textfarbe
- `background` / `background-color` - Hintergrundfarbe
- `padding` - Innenabstand
- `margin` - Außenabstand
- `font-size` - Schriftgröße
- `font-family` - Schriftart
- `border` - Rahmen
- `width` / `height` - Breite / Höhe

## Aufgabe

1. Erstellen Sie eine CSS-Datei
2. Verknüpfen Sie diese mit Ihrer HTML-Datei aus Lektion 1
3. Gestalten Sie:
   - Überschrift mit einer Farbe
   - Absatz mit anderer Schriftgröße
   - Link mit Hover-Effekt
   - Ein Element mit Klasse
   - Ein Element mit ID

## Häufige Fehler

### "Mein CSS wird nicht geladen!"
- ✅ `<link>`-Tag im `<head>` Bereich?
- ✅ Dateipfad korrekt? (`href="css/style.css"`)
- ✅ Groß-/Kleinschreibung beachtet?
- ✅ Browser-Cache geleert? (`Cmd/Ctrl + Shift + R`)

### "Meine Styles werden nicht angewendet!"
- ✅ Selektor korrekt? (`.` für Klassen, `#` für IDs)
- ✅ Klasse/ID im HTML gesetzt?
- ✅ Semikolon am Ende jeder Eigenschaft? (`color: red;`)
- ✅ Geschweifte Klammern geschlossen?

### "Farbe funktioniert nicht!"
- ✅ Eigenschaft heißt `color` für Text
- ✅ `background-color` für Hintergrund
- ✅ Farbwert korrekt? (`#FF0000`, `red`, `rgb(255, 0, 0)`)

**Mehr Hilfe:** [Häufige Fehler & Lösungen](../00-course-info/haeufige-fehler-und-loesungen.md#-css-fehler)

## Interaktives Lernen

Üben Sie Ihre Selektor-Kenntnisse spielerisch:

🍽️ **[CSS Diner](https://flukeout.github.io/)** - Ein interaktives Spiel zum Lernen von CSS-Selektoren
- Lernen Sie alle wichtigen Selektoren (Element, Klasse, ID, Kombination)
- 32 Level von einfach bis fortgeschritten
- Macht Spaß und ist lehrreich!

**Empfehlung:** Spielen Sie mindestens die ersten 15 Level nach dieser Lektion!

## Nächste Schritte

Nach Abschluss dieser Lektion fahren Sie fort mit:
→ **03-js-basics** - Lernen Sie, wie Sie Interaktivität hinzufügen
