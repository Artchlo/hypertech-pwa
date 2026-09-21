# HyperTech PWA v2 clean shell

This patch hides the Streamlit embed chrome at the bottom by clipping the
cross-origin iframe shell. It does not change Supabase, business data, or
the main Streamlit app.

Replace in the `hypertech-pwa` repository:
- `index.html`
- `service-worker.js`

Then commit to `main`, wait for GitHub Pages to redeploy, and fully close/reopen
the installed HyperTech PWA. If Android keeps an older service-worker cache,
uninstall HyperTech once and reinstall it from the GitHub Pages URL.
