# Watchout Security Apps Portal v1.0

Ово је статички портал за повезивање Watchout Security Apps Script апликација.

## Шта садржи

- `index.html` — главна страница портала
- `fuel.html`, `daily.html`, `dss.html`, `reports.html`, `schedule.html`, `kpi.html` — улазне странице за апликације
- `icons/` — PNG иконе за портал, favicon, PWA и Chrome/Windows пречице
- `manifests/` — PWA manifest за сваку апликацију
- `css/ws-portal.css` — заједнички стил
- `js/config.js` — списак апликација и placeholder линкови

## Како се користи

1. Отпремити цео садржај овог фолдера на GitHub Pages.
2. У сваком HTML фајлу заменити `PASTE_APPS_SCRIPT_URL_HERE` правим Apps Script Web App линком.
3. Отворити нпр. `fuel.html` у Chrome-у.
4. Направити Chrome/Windows пречицу.

## Важно

- Банери се не дирају.
- Apps Script апликације остају где јесу.
- Овај портал служи само за улаз, пречице, favicon, theme-color и PWA manifest.
