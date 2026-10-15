# Divy Patel: 3D SOC portfolio

Upload the CONTENTS of this folder to the ROOT of your GitHub repo (index.html, assets/, _headers, netlify.toml must be at the top level, not inside another folder).

## Deploy on Netlify
Connect the GitHub repo to Netlify. No build command and no publish directory are needed.

## Run locally
The 3D models load over HTTP, so double-clicking index.html will not work. From this folder run:

    python -m http.server 8000

then open http://localhost:8000

## Edit your content
All text lives in the DATA object near the top of the script in index.html.

Character models come from the three.js examples (MIT license).
