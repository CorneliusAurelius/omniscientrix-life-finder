# OMNISCIENTRIX • Life & Planet Finder (vΩ_138)

A single-file, offline-ready visual app that ranks exoplanets for life likelihood and maps them in 2D (sky) and 3D (galaxy) using the Omniscientrix Unified Informational Framework (vΩ).

## Features
- **Life score**: \(P_{life} \propto \exp[-|S_{env}/\hbar + D_{KL}^{atm} - \lambda A_{env}|/(\hbar \Omega_A)] \times A_G(R,z)\)
- **D_KL** atmospheric disequilibrium, **A_env** climate stability proxy, **A_G** Galactic Habitable Zone weight
- **Nivis vectors** \(\nabla_A D_{KL}\) overlay
- **IAW bridges** where |\(\delta J-\delta J_{opt}|\) dips below threshold
- **3D** interactive view (no external libs), **GHZ** overlay, **ε** recurrence pulsing
- Import custom candidate CSVs and export the current rankings
- Persistent twinkling starfields and retina-ready canvases for crisp visuals

## Run locally
Just open `index.html` in a modern browser (Chrome/Edge/Brave). No server required.

## Deploy to GitHub Pages
1. Create a new repo (e.g., `omniscientrix-life-finder`).
2. Upload the folder contents (or unzip and upload).
3. In repo Settings → Pages, set Source to **main** / **root**.
4. After a minute, your app is live at: `https://<your-username>.github.io/omniscientrix-life-finder/`

## Data
The app embeds a small demo dataset and now supports CSV import/export directly from the UI.

### Custom data import
1. Click **Import CSV** in the control panel.
2. Provide a CSV with a header row that includes at least `ra` and `dec` (degrees). Optional fields such as `distance_ly`, `radius_re`, `star_luminosity_Lsun`, `albedo`, `dkl_atm`, `a_env_proxy`, `R_kpc`, and `z_kpc` will be auto-coerced when present.
3. The status chip shows the active dataset and candidate count. Use **Restore Data** to revert to the bundled demo set at any time.

Exports include the current scores plus derived metrics (`deltaJ_raw`, `deltaJ`, `epsilon`, `Plocal`, `AG`, `Ptotal`).

## Attribution & Ethics
- © 2025 Cornelius Aurelius (Samuel Price). All rights reserved.
- Peaceful-Use Doctrine (vΩ_E): for peaceful scientific exploration only.
- When citing, reference the Omniscientrix Unified Informational Framework (vΩ), LLP calibration, and the Compass of Nivis.

