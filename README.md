# VisionAI

Live obstacle detection with voice. Camera source: this phone or an ESP32-CAM.

## Folders (put your pictures here, in the repo's main folder)
Names are read from the file names. Use .jpg, .png or .webp.

- `obstacles/` : `chair_1.jpg`, `chair_2.jpg`, `door_1.jpg` (name, then a number)
- `products/` : `parle-g--mfg-05-2025--exp-11-2026--1.jpg` (name, `--mfg-MM-YYYY`, `--exp-MM-YYYY`, `--number`)
- `currency/` : `500_1.jpg`, `100_2.jpg` (the rupee value, then a number)

Use 3 to 6 pictures of each item from different sides, with the item filling most of the picture.
After adding pictures, wait a minute, then tap "Reload pictures" in the app.

## Host on GitHub Pages
Settings, Pages, deploy from branch `main` / root. Open `https://<username>.github.io/<repo>/`.

## ESP32-CAM
Stream address: `http://<ESP-IP>:81/stream`. Same Wi-Fi as the phone. Allow "Insecure content" for the site in the browser.
Use SVGA or higher picture size to read labels.

## Notes
Distances are estimates. Wall detection is a guess from a plain view and is not a safety device.
