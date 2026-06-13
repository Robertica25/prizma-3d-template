# PRIZMA — Template flagship web imersiv & 3D

Template single-file pentru un studio digital, cu **obiect 3D real WebGL** (Three.js):
o sferă iridescentă „liquid chrome" care morfează și reacționează la mouse, plus carduri
3D-tilt, accente holografice, cursor custom, marquee, scroll reveals și contoare animate.

## Demo live
https://robertica25.github.io/prizma-3d-template/

## Tech
- Vanilla HTML/CSS/JS, **un singur fișier** (`index.html`), zero build.
- 3D: Three.js r160 (CDN, importmap) — `MeshPhysicalMaterial` cu iridescence + clearcoat,
  vertex displacement cu simplex noise, env `RoomEnvironment`, bloom (UnrealBloomPass).
  Fallback elegant pe gradient dacă WebGL nu e disponibil.
- Fonturi: Cabinet Grotesk + General Sans + Space Mono (Fontshare, free comercial).
- Accesibil: `prefers-reduced-motion`, semantic, responsive.

## Personalizare
Totul e într-un singur `index.html` — schimbi textele, numele brandului, culorile
(variabilele CSS din `:root`) și link-urile. Obiectul 3D și paleta holografică se reglează
din blocul `<script type="module">` și din `--holo` / `--cy/--vi/--mg/--go`.

Parte din librăria de template-uri **WebAgencyAI**.
