# Baugesellschaft-Brockhoff mbH – Website-Konzepte

Drei Design-Vorschläge für eine moderne Webseite der Baugesellschaft-Brockhoff mbH, Wallenhorst.

## 📋 Marketing-Konzept

**Unternehmen:** Baugesellschaft-Brockhoff mbH
**Standort:** Charlottenburger Straße 24, 49134 Wallenhorst
**Leistungen:** Hochbau, Tiefbau, Bauplanung, Hausbau, Innenausbau, Abbrucharbeiten, Außenanlagen
**Zielgruppe:** Privatpersonen & Gewerbe in der Region Osnabrück/Wallenhorst

### Kernbotschaft
> Regional verwurzelt. Full-Service. Qualität aus einer Hand.

### Marketing-Strategie
- **Vertrauensbildung** durch Projektfotos, Referenzen und lokale Verankerung
- **Klare Handlungsaufforderung** – "Anfrage stellen" und "Jetzt anrufen" prominent platziert
- **Moderne Kommunikation** – Telefon, E-Mail, WhatsApp, Kontaktformular, Google Maps
- **Vier-Stufen-Prozess** – Beratung → Planung → Umsetzung → Übergabe

---

## 🎨 Die drei Design-Varianten

### 1. Bold & Kraftvoll → `/design1-bold/index.html`
**Farben:** Dunkles Navy/Black + kräftiges Amber/Orange
**Stimmung:** Energetisch, handfest, baustark
**Zielgruppe:** Gewerbe, Großprojekte, Entscheider
**Besonderheiten:**
- Dunkles Theme für maximale Präsenz
- Orange/Amber als Akzentfarbe (Baustellenschild-Charge)
- Große Typografie mit Space Grotesk
- Floating WhatsApp-Button

### 2. Elegant & Trust → `/design2-elegant/index.html`
**Farben:** Navy Blau + Gold + Creme
**Stimmung:** Traditionell, seriös, etabliert
**Zielgruppe:** Familien, Hausbau-Kunden, Vertrauen wichtig
**Besonderheiten:**
- Klassisches Bauunternehmens-Design mit Twist
- Gold-Akzente für Premium-Anmutung
- Vier-Schritte-Prozess-Sektion
- Trust-Badges (DIQP, Meisterbetrieb, Made in Germany)
- Dezente, elegante Typografie

### 3. Modern & Minimal → `/design3-minimal/index.html`
**Farben:** Viel Weißraum + Grün-Akzente
**Stimmung:** Nachhaltig, klar, zeitgemäß
**Zielgruppe:** Umweltbewusste Bauherren, moderne Projekte
**Besonderheiten:**
- Minimalistisch und luftig
- Nachhaltigkeits-Sektion mit grünen Akzenten
- Space Grotesk für moderne Typografie
- Abgerundete Ecken (16-24px) für freundlichen Look
- Fokus auf Energieeffizienz und Ökologie

---

## 📐 Gemeinsame Elemente

Alle drei Designs enthalten:
- **Hero-Section** mit klarem Value Proposition
- **Leistungsübersicht** (6 Kernkompetenzen)
- **Projekte/Referenzen** mit Platzhaltern für Projektfotos
- **Über-uns-Sektion** mit Vertrauenssignalen
- **Kontaktbereich** mit Telefon, WhatsApp, E-Mail, Formular, Google Maps
- **Floating WhatsApp-Button** für mobilen Zugriff
- **Responsive Design** für Desktop, Tablet und Mobil
- **Footer** mit allen rechtlichen Seiten (Impressum, Datenschutz, AGB)

---

## 📁 Ordnerstruktur

```
brockhoff-bau/
├── design1-bold/
│   └── index.html      # Bold & Kraftvoll (dark + amber)
├── design2-elegant/
│   └── index.html      # Elegant & Trust (navy + gold)
├── design3-minimal/
│   └── index.html      # Modern & Minimal (white + green)
└── README.md           # Dieses Dokument
```

## 🚀 Verwendung

Jede Version ist eine eigenständige, standalone HTML-Datei. Einfach im Browser öffnen:

```bash
open design1-bold/index.html
open design2-elegant/index.html
open design3-minimal/index.html
```

Oder lokal mit Python:

```bash
python3 -m http.server 8000 --directory design1-bold/
```

## 📸 Nächste Schritte

1. **Fotos ersetzen:** Alle `[Foto: ...]`-Platzhalter mit echten Projektfotos ersetzen
2. **Inhalte anpassen:** Texte, Telefonnummern und E-Mail-Adressen finalisieren
3. **Google Maps einbetten:** Karten-Platzhalter durch echten Google Maps Embed ersetzen
4. **Formular-Backend:** Kontaktformular mit Backend verbinden (z.B. Formspree, Netlify Forms)
5. **SEO:** Meta-Tags, Open Graph, Structured Data hinzufügen
6. **Hosting:** Auf Webserver deployen (GitHub Pages, Netlify, Vercel, etc.)

---

© 2025 Erstellt für Baugesellschaft-Brockhoff mbH
