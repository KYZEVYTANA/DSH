DSH v3 — Offline Compute Lab

GitHub Pages / iPhone Safari

1. Repository root must contain index.html, manifest.webmanifest, sw.js and icon-180.png.
2. GitHub Pages: Settings -> Pages -> Deploy from a branch -> main -> /(root).
3. Open the HTTPS Pages URL in Safari.
4. Wait for DSH to load completely.
5. Run System -> self-test. WASM SHA-256 must report PASS.
6. Share -> Add to Home Screen -> keep Open as Web App enabled.
7. Launch DSH from the Home Screen once while online.
8. Turn off Wi-Fi and cellular data / use Airplane Mode.
9. Launch DSH again and verify OFFLINE plus self-test.

v3 includes:
- embedded WebAssembly SHA-256 engine;
- real Web Worker compute pool;
- benchmark and live rate;
- IndexedDB checkpoint save/resume;
- offline Service Worker cache;
- local 1–160 puzzle catalog;
- self-test and diagnostics;
- no CDN, API or runtime network dependency for core functions.

Scope limitation: DSH does not implement automated private-key brute-force/search against real Bitcoin addresses.
