# Traffic Offences

A mobile-friendly search tool for NSW traffic offences: fines, demerit points and law part codes. Pure HTML, no build step, no dependencies.

Data is a guide only (fines and points as at 1 July 2020; law part codes from the Judicial Commission of NSW). It does not replace the relevant legislation.

## Host it free on GitHub Pages

1. Sign in at github.com and click **New repository**.
2. Name it (e.g. `traffic-offences`), set it to **Public**, and click **Create repository**.
3. Click **uploading an existing file**, drag in `index.html`, `.nojekyll` and `README.md`, then **Commit changes**.
4. Go to **Settings → Pages**.
5. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main** and folder to **/ (root)**, then **Save**.
6. After about a minute your site is live at `https://YOUR-USERNAME.github.io/traffic-offences/`.

## Add to iPhone home screen

Open the site in Safari, tap **Share**, then **Add to Home Screen**.

## Updating

Edit `index.html` on GitHub (pencil icon) and commit. The site updates in a minute or two. Offences live in the `RAW` block and law part codes in the `CODES` block near the bottom of the file.

## Home screen name and icon

The app is named **NSW Traffic Offences Tool** when added to the home screen. The icon files sit next to `index.html`:

- `apple-touch-icon.png` (180x180, used by iPhone)
- `icon-192.png` and `icon-512.png` (Android and browser tabs)

To change the icon, replace those files with your own square PNGs of the same names and sizes (no transparency, no rounded corners; iOS rounds them for you).

## Light and dark mode

The site follows the device setting automatically. The sun/moon button in the header cycles Auto, Light and Dark, and remembers the choice on that device.
