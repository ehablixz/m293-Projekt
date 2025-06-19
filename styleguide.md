# **Styleguide**

## **Farbpalette**

| Variable             | Farbe     | Verwendungszweck                          |
| -------------------- | --------- | ----------------------------------------- |
| `--bg-main`          | `#070707` | Haupt-Hintergrund                         |
| `--bg-content`       | `#40434E` | Inhalts-Hintergrund                       |
| `--primary-accent`   | `#DE89BE` | Primärer Akzent (Buttons, Highlights)     |
| `--secondary-accent` | `#C297B8` | Sekundärer Akzent (Überschriften, Karten) |
| `--text-light`       | `#FDCFF3` | Helle Schriftfarbe                        |
| `--text-medium`      | `#C297B8` | Mittlere Schriftfarbe                     |
| `--text-dark`        | `#070707` | Dunkle Schriftfarbe                       |
| `--border-color`     | `#4A4E5A` | Rahmen & Trennlinien                      |

---

## **Typografie**

| Element            | Schriftart         | Verwendung            |
| ------------------ | ------------------ | --------------------- |
| `--font-primary`   | `Georgia, serif`   | Überschriften         |
| `--font-secondary` | `Lato, sans-serif` | Fließtext, Navigation |

### Schriftgrößen

| Element            | Größe     |
| ------------------ | --------- |
| Standard-Text      | `16px`    |
| Logo-Span          | `2.5rem`  |
| Logo-h1            | `1.8rem`  |
| Navigationslinks   | `1.05rem` |
| Hero-Überschrift   | `4rem`    |
| Hero-Text          | `1.5rem`  |
| Abschnittstitel    | `2.8rem`  |
| Kartenüberschrift  | `1.7rem`  |
| Kartenbeschreibung | `1rem`    |
| Seitentitel        | `3.2rem`  |
| Formular-Titel     | `2.2rem`  |

---

## **Abstände & Layout**

* Max. Inhaltsbreite: `1100px` (Hauptinhalt), `1200px` (Header)
* Standard-Padding: `1rem`, `25px`, `50px 0` (Abschnitte)
* Standard-Margin: `60px auto` (Hauptbereich)

### Grid-System

* `.card-grid`: Responsives Grid mit `auto-fit` und `minmax(300px, 1fr)`
* Lücke zwischen Karten: `35px`

---

## **Buttons**

### Primärer Call-to-Action Button

* Hintergrund: `var(--primary-accent)`
* Schriftfarbe: `var(--text-dark)`
* Padding: `16px 40px`
* Border-Radius: `50px` (abgerundete Form)
* Schatten: `var(--shadow-md)`
* Hover: dunkleres Pink `#c579a9`, Glow-Effekt

---

## **Rahmen & Ecken**

| Element          | Wert   |
| ---------------- | ------ |
| Standard-Radius  | `12px` |
| Formulareingaben | `8px`  |

---

## **Schatten**

| Variable      | Schatten                          |
| ------------- | --------------------------------- |
| `--shadow-md` | `0 5px 15px rgba(0, 0, 0, 0.2)`   |
| `--shadow-lg` | `0 10px 30px rgba(0, 0, 0, 0.25)` |

---

## **Übergänge & Effekte**

| Element          | Wert                                   |
| ---------------- | -------------------------------------- |
| Transition-Dauer | `0.3s`                                 |
| Hover-Effekte    | Navigation, Karten, Buttons, Formulare |

* Smooth Scrolling: `scroll-behavior: smooth`

---

## **Komponentenübersicht**

### Header

* Sticky (oben fixiert), transparent mit Blur-Effekt und Schatten
* Flexibles, responsives Layout

### Hero-Sektion

* Vollbild-Hintergrundbild mit linearem Farbverlauf
* Zentrierter Text

### Inhaltsabschnitte

* `.intro-section`, `.features-section`, `.class-detail-section`, `.form-container-section` mit einheitlichem vertikalen Padding
* `.section-title` mit farbiger Linie unter der Überschrift

### Karten

* Hintergrund: `var(--bg-content)`
* Rahmen mit Hover-Highlight
* Responsives Grid-Layout

### Formulare

* Zentriertes Formular mit Schatten und Rahmen
* Fokuszustand der Eingabefelder: leuchtender Rahmen

### Footer

* Dunkler Hintergrund, helle Schrift
* Einfach zentriertes Layout

---

## **Responsive Design (Responsivität)**

| Bildschirmbreite | Änderungen                                                        |
| ---------------- | ----------------------------------------------------------------- |
| `<= 768px`       | Header wird gestapelt, kleinere Schriftgrößen, einspaltige Karten |
| `<= 480px`       | Schriftgröße `15px`, kleinere Überschriften und Buttons           |
