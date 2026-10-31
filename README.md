# StrideUp – Couch to 5K (and 10K)

A running app prototype: an 8-week plan mixing walking and running, voice coaching at every switch, GPS route and pace, automatic adjustment if you take a break, and a 10K plan afterwards.

- **Free:** weeks 1–2
- **Premium (DKK 49/month or DKK 299/year):** all plans, step counter, per-run stats and Apple Health/Google Fit sync (simulated in the prototype)

## Open it

https://flowersmokeapp.github.io/StrideUp/

On a computer the app is shown inside a phone frame; on a phone it opens normally.

**Add to home screen**
- iPhone (Safari): tap Share → *Add to Home Screen*
- Android (Chrome): tap *Install* in the app, or menu ⋮ → *Install app*

## Files

| File | Contents |
| --- | --- |
| `index.html` | The whole app (HTML, CSS, JS) |
| `manifest.webmanifest` | Name, icon and colors for the home screen |
| `sw.js` | Service worker so the app works offline |
| `icons/` | App icons |

Progress and runs are stored locally in the browser on the device you use.
