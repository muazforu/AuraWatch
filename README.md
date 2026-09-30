# ⌚ Aura Watch 2026

A cinematic, scroll-driven **3D luxury watch experience** — hand-coded WebGL, zero frameworks, one HTML file.

🔗 **Live demo:** https://muazforu.github.io/AuraWatch/

## The experience

A 1500vh scroll journey through ten scenes: the reveal, time freeze, x-ray engineering views,
a quartz movement deep-dive, reassembly, 360° drag-to-inspect showcase, materials, bracelet forging,
50M water resistance, and a warped-time finale.

## Under the hood

- **Pure WebGL1** — custom matrix math, no Three.js, no libraries
- **PBR shading** — GGX microfacet specular, Schlick fresnel, image-based environment lighting
- **Post-processing** — two-pass bloom, exposure control, time-warp distortion
- **GPU particles** — gold dust, underwater bubbles, galaxy field (single draw call)
- **Procedural everything** — octagonal case, gears, Arabic dial textures all generated in code
- **Scroll-driven cinematic timeline** with buttery eased interpolation
- **Generative ambient audio** — tick + pad synthesized live with WebAudio (toggle, bottom-right)
- **Zero dependencies, zero build step** — open `index.html` and it runs

## Run it locally

Just open `index.html` in a modern desktop browser (WebGL required). For the full effect,
allow a moment for the loader, then **scroll**.

## Crafted by Techinfotics

Designed and engineered by **Techinfotics** — https://techinfotics.online

*Want a cinematic website like this for your brand? [Let's build it.](https://techinfotics.online)*
