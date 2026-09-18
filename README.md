# sfera-3d-prototyp

Interaktywna wizualizacja: niewidzialna sfera 3D, na której "przyklejone" są płaskie karty ze zdjęciami (billboardy). Sfera delikatnie się obraca, karty krążą jak chmura/kosmos. Głębia oddana przez DoF bokeh, mgłę (przyciemnienie) i subtelny bloom na froncie.

**Live:** https://sfera-3d-prototyp.vercel.app

## Technologia
- Three.js (WebGL), czysty ES-modules, jeden plik `index.html`
- Rozkład kart: Fibonacci sphere
- Post-processing: BokehPass (DoF) + UnrealBloomPass + FogExp2
- Zdjęcia placeholder: Picsum → fallback kolorowe plansze

## Sterowanie
- Przeciągnij = obróć · scroll = zoom
- Panel: prędkość obrotu, siła bokeh, bloom
