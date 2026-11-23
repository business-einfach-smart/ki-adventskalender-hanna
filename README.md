# KI-Adventskalender 2026 · Verkaufsseite

Verkaufsseite für Hannas KI-Adventskalender. Reines HTML und CSS, kein Build-Schritt. Läuft auf Netlify.

## Preis und Checkout-Link ändern

In `index.html` steht ganz oben dieser Block:

```
window.KALENDER = {
  preis: "37",
  checkoutLink: ""
};
```

Zahl oder Link eintragen und speichern (Commit). Netlify veröffentlicht die Änderung automatisch nach etwa einer Minute.
Solange `checkoutLink` leer ist, springen alle Kauf-Buttons zum Angebot auf der Seite.

## Was wo liegt

- `index.html`: die Verkaufsseite
- `impressum.html`, `datenschutz.html`: Rechtliches
- `fonts/`: Schriften lokal (Bebas Neue, Montserrat, Cormorant Garamond), keine Google Fonts
- `images/`: Logo, Produktbild, Porträt, Vorschaubild für Links (`og-image.jpg`), Favicon

Design nach Hannas Brandbook „KI Hacks“ (Version 2.0, November 2026).
