# Traffic Offences

A mobile-friendly search tool for NSW traffic offences: fines, demerit points and law part codes. Pure HTML, no build step, no dependencies.

Data is a guide only (fines and points as at 1 July 2020; law part codes from the Judicial Commission of NSW). It does not replace the relevant legislation.


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
