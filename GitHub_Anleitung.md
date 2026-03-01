# 🏒 GitHub Anleitung – ICE Hockey Homepage

---

## TEIL 1 – Einmalige Einrichtung (nur beim ersten Mal)

---

### Schritt 1: GitHub-Konto erstellen

1. Gehe auf **https://github.com**
2. Klicke oben rechts auf **"Sign up"**
3. Gib eine E-Mail-Adresse ein, wähle ein Passwort und einen Benutzernamen (z.B. `manfred-stueckler`)
4. Bestätige deine E-Mail-Adresse (GitHub schickt dir eine E-Mail)
5. Du bist jetzt eingeloggt ✅

---

### Schritt 2: Ein neues Repository erstellen

Ein **Repository** ist wie ein Ordner auf GitHub, in dem deine Website-Dateien gespeichert werden.

1. Klicke oben rechts auf das **"+"** Symbol → **"New repository"**
2. Fülle das Formular aus:
   - **Repository name:** `ice-hockey-stats` *(oder ein Name deiner Wahl, keine Leerzeichen!)*
   - **Description:** `ICE Hockey Liga Statistiken – by Manfred Stückler`
   - Wähle **"Public"** *(nur Public-Repos können kostenlos als Website gehostet werden)*
   - Hake **"Add a README file"** an ✅
3. Klicke auf **"Create repository"**

Du siehst jetzt dein leeres Repository. 🎉

---

### Schritt 3: Die HTML-Datei hochladen

1. Du bist in deinem Repository (z.B. `github.com/manfred-stueckler/ice-hockey-stats`)
2. Klicke auf **"Add file"** → **"Upload files"**
3. Ziehe die Datei **`ice_hockey.html`** in das Upload-Feld
   *(oder klicke auf "choose your files" und wähle sie aus)*
4. Warte bis "ice_hockey.html" in der Liste erscheint
5. Unten bei **"Commit changes"** schreibe in das Textfeld: `Erste Version der Homepage`
6. Klicke auf **"Commit changes"** (grüner Button)

Die Datei ist jetzt auf GitHub gespeichert. ✅

---

### Schritt 4: GitHub Pages aktivieren (macht die Seite öffentlich)

1. Klicke in deinem Repository oben auf **"Settings"** (Zahnrad-Symbol)
2. Scrolle links im Menü nach unten zu **"Pages"**
3. Unter **"Branch"** wähle: **`main`** (aus dem Dropdown) und dann **`/ (root)`**
4. Klicke auf **"Save"**
5. Warte ca. 1–2 Minuten
6. GitHub zeigt dir dann eine grüne Box mit der URL: z.B.
   `https://manfred-stueckler.github.io/ice-hockey-stats/`

> ⚠️ **Wichtig:** Die Seite heißt standardmäßig `index.html`. Deine Datei heißt aber `ice_hockey.html`.
> Das bedeutet, du musst die vollständige URL aufrufen:
> `https://manfred-stueckler.github.io/ice-hockey-stats/ice_hockey.html`
>
> **Tipp:** Wenn du die Datei in `index.html` umbenennst, reicht die kurze URL ohne Dateiname!

---

### Schritt 5: Datei umbenennen (optional, aber empfohlen)

Damit die URL kurz und schön wird:

1. Klicke in deinem Repository auf die Datei `ice_hockey.html`
2. Klicke oben rechts auf das **Stift-Symbol** (✏️ "Edit this file")
3. Klicke oben links neben dem Dateinamen auf das Feld mit `ice_hockey.html`
4. Lösche den Namen und tippe: `index.html`
5. Scrolle nach unten → **"Commit changes"** → grüner Button
6. Nach 1–2 Minuten ist die Seite erreichbar unter:
   `https://DEIN-USERNAME.github.io/ice-hockey-stats/`

---

## TEIL 2 – Seite aktualisieren (wenn Claude eine neue Version erstellt)

---

### Option A: Per Browser (einfachste Methode) ⭐

1. Gehe auf **https://github.com** und melde dich an
2. Gehe zu deinem Repository (z.B. `github.com/manfred-stueckler/ice-hockey-stats`)
3. Klicke auf die Datei **`index.html`** (oder `ice_hockey.html`)
4. Klicke oben rechts auf das **Stift-Symbol** (✏️)
5. Markiere den **gesamten Inhalt** mit `Strg + A` (Windows) oder `Cmd + A` (Mac)
6. Lösche alles mit der `Entf`-Taste
7. Kopiere den neuen HTML-Code aus Claude und füge ihn ein (`Strg + V`)
8. Scrolle nach unten → schreibe eine Beschreibung z.B. `Update: neue Spielergebnisse`
9. Klicke auf **"Commit changes"** → fertig! ✅

> Die Seite wird nach ca. 1–2 Minuten automatisch aktualisiert.

---

### Option B: Datei ersetzen (bei großen Dateien einfacher)

1. Gehe zu deinem Repository
2. Klicke auf **"Add file"** → **"Upload files"**
3. Ziehe die neue `ice_hockey.html` ins Upload-Feld
4. GitHub erkennt automatisch, dass die Datei bereits existiert und **überschreibt** sie
5. Commit-Nachricht eingeben → **"Commit changes"**
6. Fertig! ✅

---

## TEIL 3 – Häufige Fragen

---

**Frage: Wie lange dauert es, bis die Seite aktualisiert ist?**
Antwort: In der Regel 1–3 Minuten. Manchmal musst du im Browser `Strg + Shift + R` drücken, um den Cache zu leeren.

---

**Frage: Kann ich das Repository auf "Private" stellen?**
Antwort: Nein, für kostenlose GitHub Pages muss das Repository **Public** sein. Das bedeutet, jeder kann den Code sehen – aber das ist bei einer Statistik-Seite kein Problem.

---

**Frage: Was ist, wenn ich meine URL-Adresse vergesse?**
Antwort: Gehe in deinem Repository auf **Settings → Pages** – dort steht die URL immer.

---

**Frage: Kann ich mehrere Dateien hochladen?**
Antwort: Ja! Bei dieser Seite reicht aber eine einzige `index.html`, da alles darin enthalten ist (Daten, Design, Logik).

---

## ZUSAMMENFASSUNG – Auf einen Blick

| Schritt | Was | Wo |
|---------|-----|-----|
| 1 | GitHub-Konto erstellen | github.com → Sign up |
| 2 | Repository anlegen | github.com → + → New repository |
| 3 | Datei hochladen | Repository → Add file → Upload |
| 4 | GitHub Pages aktivieren | Settings → Pages → Branch: main |
| 5 | Seite aufrufen | `https://USERNAME.github.io/REPO-NAME/` |
| Update | Datei ersetzen | Datei anklicken → ✏️ → Inhalt ersetzen → Commit |

---

*Erstellt mit claude.ai – https://claude.ai*
