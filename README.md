# StrideUp – 0 til 5 km (og 10 km)

Prototype af en løbeapp: 8-ugers plan der blander gang og løb, stemme i ørerne ved hvert skift, GPS-rute og tempo, automatisk justering hvis du holder pause, og en 10 km-plan bagefter.

- **Gratis:** uge 1–2
- **Premium (49 kr./md. eller 299 kr./år):** alle planer, skridttæller, statistik pr. løb og Apple Health/Google Fit-sync (simuleret i prototypen)

## Åbn den

Appen køres via GitHub Pages. På en computer vises den i en telefonramme med en QR-kode; på mobilen åbner den normalt.

**Gem på hjemmeskærmen**
- iPhone (Safari): tryk på Del → *Føj til hjemmeskærm*
- Android (Chrome): tryk *Installer* i appen eller i menuen ⋮ → *Installer app*

## Filer

| Fil | Indhold |
| --- | --- |
| `index.html` | Hele appen (HTML, CSS, JS) |
| `manifest.webmanifest` | Navn, ikon og farver til hjemmeskærmen |
| `sw.js` | Service worker, så appen virker offline |
| `icons/` | App-ikoner |

Data (fremskridt og løb) gemmes lokalt i browseren på den enhed, du bruger.
