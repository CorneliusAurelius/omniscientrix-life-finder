# OMNISCIENTRIX • Life & Planet Finder (vΩ_138)

A single-file, offline-ready visual app that ranks exoplanets for life likelihood and maps them in 2D (sky) and 3D (galaxy) using the Omniscientrix Unified Informational Framework (vΩ).

## Features
- **Life score**: \(P_{life} \propto \exp[-|S_{env}/\hbar + D_{KL}^{atm} - \lambda A_{env}|/(\hbar \Omega_A)] \times A_G(R,z)\)
- **D_KL** atmospheric disequilibrium, **A_env** climate stability proxy, **A_G** Galactic Habitable Zone weight
- **Nivis vectors** \(\nabla_A D_{KL}\) overlay
- **IAW bridges** where |\(\delta J\)| dips below threshold
- **3D** interactive view (no external libs), **GHZ** overlay, **ε** recurrence pulsing
- Export ranked CSV

## Run locally
Just open `index.html` in a modern browser (Chrome/Edge/Brave). No server required.

## Deploy to GitHub Pages
1. Create a new repo (e.g., `omniscientrix-life-finder`).
2. Upload the folder contents (or unzip and upload).
3. In repo Settings → Pages, set Source to **main** / **root**.
4. After a minute, your app is live at: `https://<your-username>.github.io/omniscientrix-life-finder/`

## Data
The app embeds a small demo dataset. To use your own, edit the `DATA` JSON in `index.html` or adjust the code to load a CSV via `<input type="file">` (optional enhancement).

**Data fields**: `name, ra, dec, distance_ly, radius_re, star_luminosity_Lsun, albedo, dkl_atm, a_env_proxy, R_kpc, z_kpc`.

## Attribution & Ethics
- © 2025 Cornelius Aurelius (Samuel Price). All rights reserved.
- Peaceful-Use Doctrine (vΩ_E): for peaceful scientific exploration only.
- When citing, reference the Omniscientrix Unified Informational Framework (vΩ), LLP calibration, and the Compass of Nivis.

