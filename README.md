# Die Fremde Reinheit — Riss Archives

Ein Crossover-Universum zwischen Warhammer 40,000 und Star Wars.  
Erzählt aus der Perspektive derer, die dazwischen stehen.

**Live:** [mc-grimdark.github.io/riss-archives](https://mc-grimdark.github.io/riss-archives/)

---

## Struktur

```
/
├── index.html              ← Startseite
├── rahmenordnung.html      ← Framework: Fraktionen, Regeln, Kräfteverhältnisse
├── erzaehlungen.html       ← Kapitelliste
├── style.css               ← Stylesheet (geteilt)
└── kapitel/
    ├── prolog.html
    ├── kapitel-i.html
    ├── kapitel-ii.html
    ├── kapitel-iii.html
    ├── kapitel-iv.html
    ├── kapitel-v.html
    └── epilog.html
```

**Rahmenordnung** beschreibt, *was* das Universum ist.  
**Erzählungen** zeigen, wie es sich *anfühlt*.  

Beides ist getrennt. Beides gehört zusammen.

---

## Neue Kapitel hinzufügen

1. Kopiere eine bestehende Kapitel-Datei (z.B. `kapitel/kapitel-v.html`).
2. Ersetze den Text im `<div class="prose">` Block durch den neuen Text.
3. Passe Titel, Untertitel und Tags an.
4. Aktualisiere die Vor/Zurück-Navigation am Ende.
5. Trage das neue Kapitel in `erzaehlungen.html` ein.

Kein Build-System nötig. Reines HTML/CSS. Texteditor reicht.

---

## Neue Erzählungen hinzufügen

Das Universum ist nicht auf eine Erzählung beschränkt. Für eine neue Erzählung:

1. Erstelle einen neuen Unterordner (z.B. `kapitel-zweite-erzaehlung/`).
2. Trage die Erzählung mit eigenem Abschnitt in `erzaehlungen.html` ein.
3. Prüfe, ob die Rahmenordnung erweitert werden muss.

---

## Technik

- Reines HTML + CSS, keine Abhängigkeiten
- Gehostet über [GitHub Pages](https://pages.github.com/)
- Fonts via Google Fonts (Cinzel, Crimson Pro, JetBrains Mono)
- Änderungen werden nach Push automatisch live

---

## Disclaimer

This is a non-commercial fan project.  
All Warhammer 40,000 elements are the intellectual property of **Games Workshop Ltd.**  
All Star Wars elements are the intellectual property of **Lucasfilm / Disney.**  
This site generates no revenue and claims no ownership of these properties.  
It exists solely as a creative exercise and tribute by fans, for fans.
