# Robert Popa — Portofoliu personal (web imersiv & 3D)

Site de prezentare single-file: cine sunt, ce fac, cu ce tehnologii. Construit ca dovadă
de skill — încărcat cu tehnologie, optimizat și unic.

## Demo live
https://robertica25.github.io/prizma-3d-template/

## Ce conține (tehnologii la vedere)
- **3D real-time WebGL** (Three.js) — obiect iridescent „liquid chrome" care morfează și
  reacționează la mouse, cu bloom. Geometrie optimizată (detail 24) + DPR cap + init deferit
  după primul paint + pauză când tab-ul nu e vizibil → fluid și pe plăci modeste.
- **Constelație interactivă** pe Canvas 2D (rulează doar când e vizibilă).
- Cursor custom, butoane magnetice, bară de progres scroll, text „typed", contoare animate,
  marquee, carduri tilt, scroll reveals, grain.
- Secțiuni: hero, despre, stack (skill-uri grupate), proiecte, lab interactiv, contact.

## Performanță & contrast
- Conținutul apare instant (nu așteaptă CDN-ul 3D); 3D-ul se încarcă separat.
- Text pe scrim întunecat + gradient holografic luminos cu glow → lizibilitate bună peste animație.

## Tehnic
- Vanilla HTML/CSS/JS, **un singur fișier** `index.html`, zero build.
- Three.js r160 (CDN, importmap). Fonturi Fontshare (Cabinet Grotesk + General Sans + Space Mono).
- Accesibil: `prefers-reduced-motion`, semantic, responsive. Schema.org `Person`.

Personalizare: totul e în `index.html` — texte, link-uri sociale, culori (variabile CSS din `:root`).
