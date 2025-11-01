# Entwicklungsumgebung Setup

Ein Schritt-für-Schritt-Guide für die perfekte Einrichtung Ihrer Entwicklungsumgebung.

---

## 📋 Voraussetzungen

Bevor Sie mit dem Kurs starten, benötigen Sie:

1. ✅ Einen Computer (Mac, Windows oder Linux)
2. ✅ Internetverbindung
3. ✅ Etwa 30 Minuten Zeit für das Setup

---

## 1. 🌐 Browser installieren

Sie benötigen einen **modernen Browser** mit guten Developer Tools.

### Empfohlene Browser (wählen Sie einen):

**Option 1: Google Chrome** (empfohlen für Anfänger)
- Download: https://www.google.com/chrome/
- Vorteile: Beste DevTools, viele Tutorials basieren darauf
- Tastenkombination DevTools: `Cmd + Option + I` (Mac) oder `F12` (Windows)

**Option 2: Mozilla Firefox**
- Download: https://www.mozilla.org/firefox/
- Vorteile: Gute Privatsphäre, ausgezeichnete CSS-Grid-Tools

**Option 3: Microsoft Edge**
- Download: https://www.microsoft.com/edge
- Vorteile: Basiert auf Chromium, bereits auf Windows vorinstalliert

⚠️ **Nicht empfohlen:** Safari (begrenzte DevTools), Internet Explorer (veraltet)

---

## 2. 💻 Code-Editor installieren

### Visual Studio Code (VS Code) - STARK EMPFOHLEN

**Download:** https://code.visualstudio.com/

**Warum VS Code?**
- ✅ Kostenlos und Open Source
- ✅ Hervorragende Extensions
- ✅ Integriertes Terminal
- ✅ Git-Integration
- ✅ IntelliSense (Code-Vervollständigung)
- ✅ Funktioniert auf Mac, Windows & Linux

### Installation:

**Mac:**
1. DMG-Datei herunterladen
2. VS Code in den Programme-Ordner ziehen
3. Öffnen und erlauben

**Windows:**
1. EXE-Datei herunterladen
2. Installer ausführen
3. Bei Installation: "Add to PATH" aktivieren (wichtig!)

**Linux:**
```bash
# Ubuntu/Debian
sudo snap install code --classic
```

---

## 3. 🔌 VS Code Extensions installieren

Extensions erweitern die Funktionalität von VS Code.

### Essential Extensions (MÜSSEN installiert werden):

#### 1. **Live Server**
- **Autor:** Ritwick Dey
- **Zweck:** Automatisches Neu-Laden der Seite bei Änderungen
- **Installation:**
  1. Öffnen Sie VS Code
  2. Klicken Sie auf Extensions-Icon (links, 4 Quadrate)
  3. Suchen Sie "Live Server"
  4. Klicken Sie "Install"

**Verwendung:**
- Rechtsklick auf `index.html` → "Open with Live Server"
- Oder: Button "Go Live" unten rechts in VS Code

#### 2. **Prettier - Code Formatter**
- **Autor:** Prettier
- **Zweck:** Automatische Code-Formatierung
- **Installation:** Wie oben, suchen Sie "Prettier"

**Einrichtung:**
1. VS Code Einstellungen öffnen (`Cmd + ,` oder `Ctrl + ,`)
2. Suchen Sie "Format On Save"
3. Aktivieren Sie das Häkchen ✓

#### 3. **HTML CSS Support**
- **Autor:** ecmel
- **Zweck:** CSS-Klassen-Autovervollständigung in HTML
- **Installation:** Suchen Sie "HTML CSS Support"

### Empfohlene Extensions (optional, aber hilfreich):

#### 4. **Auto Rename Tag**
- **Autor:** Jun Han
- **Zweck:** Ändert automatisch den schließenden Tag beim Bearbeiten des öffnenden Tags

#### 5. **Color Highlight**
- **Autor:** Sergii Naumov
- **Zweck:** Zeigt Farben direkt im Code an

#### 6. **Path Intellisense**
- **Autor:** Christian Kohler
- **Zweck:** Autovervollständigung für Dateipfade

#### 7. **Indent Rainbow**
- **Autor:** oderwat
- **Zweck:** Farbige Einrückungen für bessere Lesbarkeit

#### 8. **Error Lens**
- **Autor:** Alexander
- **Zweck:** Zeigt Fehler direkt inline im Code

---

## 4. ⚙️ VS Code Einstellungen optimieren

### Öffnen Sie die Einstellungen:
- Mac: `Cmd + ,`
- Windows/Linux: `Ctrl + ,`

### Empfohlene Einstellungen:

1. **Format On Save aktivieren**
   - Suchen: "Format On Save"
   - ✓ Aktivieren

2. **Auto Save aktivieren**
   - Suchen: "Auto Save"
   - Wählen: "afterDelay"

3. **Tab Size auf 2 setzen**
   - Suchen: "Tab Size"
   - Wert: `2`

4. **Word Wrap aktivieren**
   - Suchen: "Word Wrap"
   - Wählen: "on"

5. **Minimap (optional)**
   - Suchen: "Minimap"
   - Deaktivieren wenn störend

---

## 5. 📁 Projekt-Ordner erstellen

### Empfohlene Ordnerstruktur:

```
Dokumente/
└── Webentwicklung/
    └── IM1-Kurs/
        ├── 01-html-basics/
        ├── 02-css-basics/
        ├── 03-js-basics/
        └── ...
```

### Ordner in VS Code öffnen:

1. VS Code öffnen
2. `File` → `Open Folder` (oder `Cmd + O` / `Ctrl + O`)
3. Wählen Sie Ihren Kurs-Ordner
4. VS Code zeigt nun alle Dateien im Sidebar

**Tipp:** Öffnen Sie immer den **gesamten Projekt-Ordner**, nicht einzelne Dateien!

---

## 6. 🖥️ Terminal / Command Line Grundlagen

### Terminal in VS Code öffnen:

- Mac/Linux: `` Ctrl + ` `` oder `Terminal` → `New Terminal`
- Windows: `` Ctrl + ` `` oder `Terminal` → `New Terminal`

### Nützliche Befehle:

```bash
# Aktuelles Verzeichnis anzeigen
pwd

# Dateien im Verzeichnis auflisten
ls        # Mac/Linux
dir       # Windows

# In ein Verzeichnis wechseln
cd ordnername

# Ein Verzeichnis nach oben
cd ..

# Neues Verzeichnis erstellen
mkdir ordnername

# Datei erstellen (Mac/Linux)
touch index.html

# Datei erstellen (Windows)
type nul > index.html
```

**Für den Kurs:** Sie brauchen das Terminal meist nicht! Live Server macht alles automatisch.

---

## 7. 🔍 Browser DevTools kennenlernen

### DevTools öffnen:

- **Mac:** `Cmd + Option + I`
- **Windows/Linux:** `F12` oder `Ctrl + Shift + I`
- **Rechtsklick auf Element:** "Element untersuchen"

### Wichtige Tabs:

#### 1. **Elements / Elemente**
- HTML-Struktur live ansehen und bearbeiten
- CSS-Styles inspizieren und testen
- Box Model visualisieren

**Übung:** Rechtsklick auf ein Element → "Untersuchen"

#### 2. **Console / Konsole**
- JavaScript-Fehler sehen (SEHR WICHTIG!)
- `console.log()` Ausgaben
- JavaScript direkt testen

**Übung:** Tippen Sie in der Konsole: `console.log("Hallo!")`

#### 3. **Network / Netzwerk**
- Zeigt alle geladenen Dateien
- Prüft, ob CSS/JS geladen wurde
- Hilfreich bei 404-Fehlern (Datei nicht gefunden)

#### 4. **Sources / Quellen**
- JavaScript debuggen
- Breakpoints setzen
- Code Schritt für Schritt durchgehen

---

## 8. ✅ Installation testen

### Test-Projekt erstellen:

1. **Ordner erstellen:**
   ```
   test-projekt/
   ├── index.html
   ├── css/
   │   └── style.css
   └── js/
       └── script.js
   ```

2. **index.html erstellen:**
   ```html
   <!DOCTYPE html>
   <html lang="de">
   <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>Setup Test</title>
       <link rel="stylesheet" href="css/style.css">
   </head>
   <body>
       <h1>Setup erfolgreich!</h1>
       <p>Wenn Sie diese Seite sehen und die DevTools öffnen können, ist alles korrekt eingerichtet.</p>
       <button id="testButton">Klick mich!</button>

       <script src="js/script.js"></script>
   </body>
   </html>
   ```

3. **css/style.css erstellen:**
   ```css
   body {
       font-family: Arial, sans-serif;
       max-width: 800px;
       margin: 50px auto;
       padding: 20px;
       background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
       color: white;
   }

   h1 {
       color: #fff;
   }

   button {
       background: white;
       color: #667eea;
       border: none;
       padding: 10px 20px;
       font-size: 16px;
       border-radius: 5px;
       cursor: pointer;
   }

   button:hover {
       background: #f0f0f0;
   }
   ```

4. **js/script.js erstellen:**
   ```javascript
   console.log("✅ JavaScript erfolgreich geladen!");

   const button = document.getElementById('testButton');

   button.addEventListener('click', () => {
       alert("🎉 Alles funktioniert perfekt!");
       console.log("Button wurde geklickt!");
   });
   ```

5. **Testen:**
   - Rechtsklick auf `index.html` → "Open with Live Server"
   - Seite sollte im Browser öffnen
   - DevTools öffnen (F12)
   - In der Konsole sollte "✅ JavaScript erfolgreich geladen!" stehen
   - Button klicken → Alert sollte erscheinen

### Wenn alles funktioniert:
✅ Browser zeigt die Seite mit Styling
✅ Console zeigt die Nachricht
✅ Button löst Alert aus
✅ Änderungen werden automatisch neu geladen (Live Server)

🎉 **Herzlichen Glückwunsch! Sie sind bereit für den Kurs!**

---

## 🆘 Problemlösung

### Live Server startet nicht:
- Haben Sie die Extension installiert?
- Rechtsklick auf eine `.html` Datei (nicht `.css` oder `.js`)
- Neustart von VS Code

### Prettier formatiert nicht automatisch:
- "Format On Save" aktiviert?
- Prettier als Standard-Formatter eingestellt?
- Settings: "Default Formatter" → "Prettier"

### Änderungen werden nicht angezeigt:
- Läuft Live Server? (Unten rechts "Port: 5500")
- Browser-Cache leeren: `Cmd/Ctrl + Shift + R`
- Datei gespeichert?

### VS Code findet Dateien nicht:
- Öffnen Sie den **ganzen Ordner**, nicht einzelne Dateien
- `File` → `Open Folder`

---

## 📚 Nächste Schritte

1. ✅ Installation abgeschlossen
2. ✅ Test-Projekt funktioniert
3. ➡️ Beginnen Sie mit dem Kurs: [01-html-basics](../01-html-basics/)

---

## 💡 Tipps für den Alltag

### VS Code Shortcuts (lernen Sie diese auswendig!):

**Mac:**
- `Cmd + S` - Speichern
- `Cmd + P` - Datei schnell öffnen
- `Cmd + Shift + P` - Command Palette
- `Cmd + /` - Zeile kommentieren/entkommentieren
- `Cmd + D` - Nächstes Vorkommen auswählen
- `Option + Shift + ↓/↑` - Zeile duplizieren

**Windows/Linux:**
- `Ctrl + S` - Speichern
- `Ctrl + P` - Datei schnell öffnen
- `Ctrl + Shift + P` - Command Palette
- `Ctrl + /` - Zeile kommentieren/entkommentieren
- `Ctrl + D` - Nächstes Vorkommen auswählen
- `Alt + Shift + ↓/↑` - Zeile duplizieren

### Best Practices:

1. **Speichern Sie regelmäßig!** (`Cmd/Ctrl + S`)
2. **Nutzen Sie Auto Save** (siehe Einstellungen)
3. **Öffnen Sie die DevTools** bei jedem Test
4. **Lesen Sie Fehlermeldungen** in der Konsole
5. **Nutzen Sie Prettier** für sauberen Code

---

**Sie sind jetzt bereit! Viel Erfolg im Kurs! 🚀**
