QSkill Slab 1 — Spotify/RapidAPI starter

Files: index.html, app.js, README.txt.

The screenshots showed GET downloadMusic and a required `link` parameter, but not the API host/provider or response schema. These details are provider-specific, so the code uses placeholders instead of guessing.

Setup:
1. Open the provider's RapidAPI page and choose Code Snippets (JavaScript/fetch).
2. Copy the host, full endpoint URL, and key into app.js.
3. Inspect the provider's sample response and set RESPONSE_AUDIO_URL_PATH to the exact field containing a permitted download URL.
4. Test with audio you are authorized to download.

Security: Never commit a RapidAPI key to a public GitHub repository. Browser-side keys are visible to users; use a backend proxy for public deployment. Only use a service authorized to distribute the requested audio.
