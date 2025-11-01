# Lektion 1: HTML Grundlagen

## Lernziele

Nach dieser Lektion können Sie:
- Die Grundstruktur einer HTML-Datei verstehen und erstellen
- Semantische HTML-Elemente korrekt einsetzen
- HTML-Attribute verwenden (class, id, src, href, alt)
- Den Unterschied zwischen Klassen und IDs verstehen

## Inhalte

### 📚 Lesson (Theorie)
Im Ordner `lesson/` finden Sie:
- `05 HTML Boilerplate.md` - Die HTML-Grundstruktur
- `10 HTML-Elemente.md` - Übersicht wichtiger HTML-Elemente
- `15 was sind CSS.md` - Einführung in CSS
- `17 Aufbau der CSS-Datei.md` - CSS-Dateistruktur
- `22 Aufbau der JavaScript-Datei.md` - JavaScript-Dateistruktur

### 💡 Examples (Beispiele)
Im Ordner `examples/` finden Sie ein vollständiges Beispiel mit:
- `index.html` - HTML-Datei mit allen wichtigen Elementen
- `css/style.css` - Zugehöriges Stylesheet
- `js/script.js` - Zugehöriges JavaScript

### ✏️ Exercises (Übungen)
Im Ordner `exercises/` können Sie Ihre eigenen Übungen erstellen.

## Aufgabe

Erstellen Sie eine eigene HTML-Datei mit:
1. Korrekter HTML5-Grundstruktur (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`)
2. Mindestens einer Überschrift (`<h1>`)
3. Mindestens einem Absatz (`<p>`)
4. Einem Bild (`<img>`)
5. Einem Link (`<a>`)
6. Mindestens einer Klasse (`class=""`)
7. Mindestens einer ID (`id=""`)

## Wichtige HTML-Elemente

- `<h1>` bis `<h6>` - Überschriften
- `<p>` - Absatz
- `<a href="...">` - Link
- `<img src="..." alt="...">` - Bild
- `<div>` - Container (generisch)
- `<main>`, `<header>`, `<footer>`, `<nav>`, `<section>` - Semantische Container

## Häufige Fehler

### "Mein Bild wird nicht angezeigt!"
- ✅ Ist der Dateipfad korrekt? (`src="images/foto.jpg"`)
- ✅ Groß-/Kleinschreibung beachtet?
- ✅ Dateiendung korrekt? (.jpg, .png, .gif)
- ✅ Liegt die Bilddatei wirklich im angegebenen Ordner?

### "Mein Link funktioniert nicht!"
- ✅ `href`-Attribut gesetzt? (`<a href="...">`)
- ✅ Dateipfad korrekt?
- ✅ Bei externen Links: `https://` am Anfang?

### "Umlaute werden falsch angezeigt!"
- ✅ `<meta charset="UTF-8">` im `<head>`?
- ✅ Datei als UTF-8 gespeichert? (VS Code macht das automatisch)

**Mehr Hilfe:** [Häufige Fehler & Lösungen](../00-course-info/haeufige-fehler-und-loesungen.md)

## Nächste Schritte

Nach Abschluss dieser Lektion fahren Sie fort mit:
→ **02-css-basics** - Lernen Sie, wie Sie Ihre HTML-Seiten gestalten
