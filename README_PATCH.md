# HyperTech PWA v3 footer-cover patch

This version uses a parent-layer overlay on mobile to physically cover the
Streamlit embed strip ("Built with Streamlit / Fullscreen").

Replace these files in the `hypertech-pwa` repository:
- index.html
- service-worker.js

Commit to `main`. Wait for GitHub Pages to redeploy.

Because Android PWAs can retain a service worker aggressively, if the old strip
still appears after the GitHub Pages update:
1. uninstall HyperTech from the phone,
2. open https://artchlo.github.io/hypertech-pwa/ in Chrome,
3. refresh once,
4. install HyperTech again.
